# bad-stats
Miscellaneous examples of bad and terrible statistics. This is *neither* a systematic collection of statistical errors *nor* a pillory for the sources from which the examples originated. The mistakes and problems outlined below are pretty common and I just happened to stumble across them in the publications I often read. The fact that you see a lot of bad examples from Swiss media outlets does not meand that Swiss journalists are particularly bad at statistics. It just means that I read Swiss newspapers more often than foreign ones.  

Did you stumble across a good example for bad stats? Then send me an [e-mail](ervan.grueninger@protonmail.com) or send a pull request with a quick explanation of why you believe it’s bad statistics.

## Using circles for data visualisations
Circles are bad for representing numbers as their area doubles with only a
&radic;2 increase of the radius:

![Image source: NZZ, "Die grossen Flugplätze wachsen, die kleinen schrumpfen"](https://raw.githubusercontent.com/segrue/bad-stats/master/fig/flughaefen-und-flugplaetze.jpg)

Image source: [NZZ, "Die grossen Flugplätze wachsen, die kleinen schrumpfen"](https://www.nzz.ch/schweiz/schweizerische-regionalflugplaetze-die-grossen-flugplaetze-wachsen-die-kleinen-schrumpfen-ld.146496)

![Image source: Al Gore/TED 12:15](https://raw.githubusercontent.com/segrue/bad-stats/master/fig/BurnableFossilFuels.png)

Image source: [Al Gore/TED 12:15](http://www.ted.com/talks/al_gore_the_case_for_optimism_on_climate_change#t-733372)

Incidentally, this is the reason why you should refrain from using [pie charts](http://www.businessinsider.com/pie-charts-are-the-worst-2013-6?IR=T) in most scenarios.

## Comparing Apples and Oranges
When making comparisons between different units (population groups, countries etc.), it is important to pick the correct variables to compare them with each other. 

In the following example, percentage of smokers in a countries are plotted against the price of a pack of cigarettes in those countries. At first glance, the plot seems to indicate that cigarette prices are not correlated to percentages of smokers in a country. However, the prices are not adjusted for purchasing power, hence making the comparison between the different countries pretty much pointless. After all, $5 for a pack of cigarettes might be not much for a Swiss smoker, but is rather expensive for a Tanzanian smoker.

![Image source: Watson, "Diese Weltkarte zeigt, in welchem Land am meisten geraucht wird"](https://raw.githubusercontent.com/segrue/bad-stats/master/fig/raucheranteil-und-zigarettenpreise.png)

Image source: [Watson, "Diese Weltkarte zeigt, in welchem Land am meisten geraucht wird"](https://www.watson.ch/wissen/die%20welt%20in%20karten/812614572-diese-weltkarte-zeigt-welche-nationen-am-meisten-rauchen)

## Questionable fits
Many scatter plots often contain a regression line to highlight the supposed trend of the data. Often, this comes down to a linear regression line---even in cases in which the data does not warrant a linear fit. 

The following scatter plot shows the percentage of childern entering highschool in a given community plotted against the respective ["Sozialindex"](https://www.bista.zh.ch/_pub/sozialindex.aspx), a metric used by the canton of Zurich to measure the social burden within a given community. The regression fit could be visibly improved if a quadratic and not a linear fit would be used.

![Image source: Tages-Anzeiger, "Wo es viele Kinder ans Gymi schaffen"](https://raw.githubusercontent.com/segrue/bad-stats/master/fig/sozialindex-gymiuebertritt.jpg)

Image source: [Tages-Anzeiger, "Wo es viele Kinder ans Gymi schaffen"](https://www.tagesanzeiger.ch/zuerich/region/wo-es-viele-kinder-ans-gymi-schaffen/story/30076325?) / [Philippe Wampfler via FB](https://www.facebook.com/photo.php?fbid=10218088750266703&set=a.1048987301351&type=3&theater&comment_id=10218089695050322&notif_t=feedback_reaction_generic&notif_id=1555516296775305)

## Other things terribly visualised
For more terrible data visualisations, see [WTF Visualisations](http://viz.wtf/)
