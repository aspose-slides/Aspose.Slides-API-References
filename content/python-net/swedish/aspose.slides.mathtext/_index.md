---
title: aspose.slides.mathtext
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/
---
Innehåller klasser för arbete med matematisk text i Microsoft PowerPoint-presentationer.
## Klasser

| Klass | Beskrivning |
| :- | :- |
| [`BaseScript`](/slides/python-net/sv/aspose.slides.mathtext/basescript/) | Matematiskt skript |
| [`IMathAccent`](/slides/python-net/sv/aspose.slides.mathtext/imathaccent/) | Anger accentfunktionen, bestående av en bas och ett kombinerande diakritiskt tecken<br/>            Exempel: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathaccentfactory/) | Tillåter att skapa en matematisk accent |
| [`IMathArray`](/slides/python-net/sv/aspose.slides.mathtext/imatharray/) | Anger en vertikal samling av ekvationer eller valfri matematiska objekt |
| [`IMathArrayFactory`](/slides/python-net/sv/aspose.slides.mathtext/imatharrayfactory/) | Tillåter att skapa en matematisk matris |
| [`IMathBar`](/slides/python-net/sv/aspose.slides.mathtext/imathbar/) | Anger bar-funktionen, bestående av ett basargument och en över- eller understreck |
| [`IMathBarFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathbarfactory/) | Tillåter att skapa ett matematiskt streck |
| [`IMathBlock`](/slides/python-net/sv/aspose.slides.mathtext/imathblock/) | Anger en instans av matematisk text som finns inom ett MathParagraph och börjar på en egen rad.<br/>            Alla matematiska zoner, inklusive ekvationer, uttryck, samlingar av ekvationer eller uttryck, och formler representeras av ett math block. |
| [`IMathBlockCollection`](/slides/python-net/sv/aspose.slides.mathtext/imathblockcollection/) | Samling av math block (IMathBlock) |
| [`IMathBlockFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathblockfactory/) | Tillåter att skapa ett math block |
| [`IMathBorderBox`](/slides/python-net/sv/aspose.slides.mathtext/imathborderbox/) | Ritar en rektangulär eller annan kant runt IMathElement. |
| [`IMathBorderBoxFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathborderboxfactory/) | Tillåter att skapa en math border box |
| [`IMathBox`](/slides/python-net/sv/aspose.slides.mathtext/imathbox/) | Anger den logiska inramningen (paketeringen) av ett matematiskt element.<br/>            Till exempel kan ett inramat objekt fungera som en operatoremulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytning, eller grupperas så att radbrytningar inte tillåts inom.<br/>            Till exempel bör operatorn \"==\" inramas för att förhindra radbrytningar. |
| [`IMathBoxFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathboxfactory/) | Tillåter att skapa en math box |
| [`IMathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/imathdelimiter/) | Anger delimitatorobjektet, bestående av öppnings- och stängningstecken (såsom parenteser, <br/>            klammerparenteser, hakparenteser och vertikala streck), och ett eller flera matematiska element inuti, separerade av ett specificerat tecken.<br/>            Exempel: (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathdelimiterfactory/) | Tillåter att skapa en math delimiter |
| [`IMathElement`](/slides/python-net/sv/aspose.slides.mathtext/imathelement/) | Basgränssnitt för alla matematiska element: <br/>            bråk, matematisk text, funktion, uttryck med flera element osv |
| [`IMathElementCollection`](/slides/python-net/sv/aspose.slides.mathtext/imathelementcollection/) | Representerar en samling av matematiska element (MathElement). |
| [`IMathFraction`](/slides/python-net/sv/aspose.slides.mathtext/imathfraction/) | Anger bråkobjektet, bestående av en täljare och en nämnare separerade av en bråkstreck.<br/>            Bråkstrecket kan vara horisontellt eller diagonalt, beroende på bråkets egenskaper.<br/>            Bråkobjektet används även för att representera stack-funktionen, som placerar ett element ovanpå ett annat, utan bråkstreck. |
| [`IMathFractionFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathfractionfactory/) | Tillåter att skapa ett math bråk |
| [`IMathFunction`](/slides/python-net/sv/aspose.slides.mathtext/imathfunction/) | Anger en funktion av ett argument. |
| [`IMathFunctionFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathfunctionfactory/) | Tillåter att skapa en math funktion |
| [`IMathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacter/) | Anger en grupperingstegn ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan element |
| [`IMathGroupingCharacterFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathgroupingcharacterfactory/) | Tillåter att skapa ett math grupperingstecken |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | Anger Sub-Superscript-objektet, som består av en bas <br/>            och en nedsänkt och upphöjd index placerad till vänster om basen. |
| [`IMathLimit`](/slides/python-net/sv/aspose.slides.mathtext/imathlimit/) | Anger Limit-objektet, bestående av text på baslinjen och förminskad text omedelbart ovanför eller nedanför den. |
| [`IMathLimitFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathlimitfactory/) | Tillåter att skapa IMathLimit |
| [`IMathMatrix`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/) | Anger Matrix-objektet, bestående av underordnade element arrangerade i en eller flera rader och kolumner. <br/>            Det är viktigt att notera att matriser inte har inbyggda delimitatorer. <br/>            För att placera matrisen i hakparenteserna bör du använda delimitatorobjektet (IMathDelimiter).<br/>            Null-argument kan användas för att skapa luckor i matriser. |
| [`IMathMatrixFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrixfactory/) | Tillåter att skapa en math matris |
| [`IMathNaryOperator`](/slides/python-net/sv/aspose.slides.mathtext/imathnaryoperator/) | Anger ett N-ärt matematiskt objekt, såsom Summation och Integral.<br/>            Det består av en operator, en bas (eller operand), och valfria övre och nedre gränser. <br/>            Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral |
| [`IMathNaryOperatorFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathnaryoperatorfactory/) | Tillåter att skapa IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/sv/aspose.slides.mathtext/imathnaryoperatorproperties/) | Anger egenskaper för IMathNaryOperator |
| [`IMathParagraph`](/slides/python-net/sv/aspose.slides.mathtext/imathparagraph/) | Matematisk paragraf som är en behållare för matematiska block (IMathBlock) |
| [`IMathParagraphFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathparagraphfactory/) | Tillåter att skapa en math paragraf |
| [`IMathPhantom`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/) | Representerar ett phantom math-objekt (<m:phant>) som påverkar layouten för dess underordnade element<br/>            utan nödvändigtvis att visas. Ett phantom kan dölja dess basuttryck samtidigt som det bevarar<br/>            dess bredd, höjd eller djup för att justera formler eller reservera utrymme. <br/>            Synlighet och geometribeteende styrs av egenskaper som Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc och Transp. |
| [`IMathPortion`](/slides/python-net/sv/aspose.slides.mathtext/imathportion/) | Representerar en del med matematisk kontext inuti. |
| [`IMathRadical`](/slides/python-net/sv/aspose.slides.mathtext/imathradical/) | Anger radikalfunktionen, bestående av en bas och en valfri grad.<br/>            Exempel på radikalobjekt är √𝑥. |
| [`IMathRadicalFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathradicalfactory/) | Tillåter att skapa en math radikal |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | Anger Sub-Superscript-objektet, som består av en bas <br/>            och en nedsänkt och upphöjd index placerad till höger om basen. |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | Tillåter att skapa IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/imathsubscriptelement/) | Anger subscript-objektet, som består av en bas <br/>            och en förminskad subscript placerad nedanför och till höger. |
| [`IMathSubscriptElementFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathsubscriptelementfactory/) | Tillåter att skapa IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/imathsuperscriptelement/) | Anger superscript-objektet, som består av en bas <br/>            och en förminskad superscript placerad ovanför och till höger |
| [`IMathSuperscriptElementFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathsuperscriptelementfactory/) | Tillåter att skapa IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/sv/aspose.slides.mathtext/imathematicaltext/) | Matematisk text |
| [`IMathematicalTextFactory`](/slides/python-net/sv/aspose.slides.mathtext/imathematicaltextfactory/) | Tillåter att skapa ett MathematicalText-element |
| [`MathAccent`](/slides/python-net/sv/aspose.slides.mathtext/mathaccent/) | Anger accentfunktionen, bestående av en bas och ett kombinerande diakritiskt tecken<br/>            Exempel: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathaccentfactory/) | Tillåter att skapa en math accent |
| [`MathArray`](/slides/python-net/sv/aspose.slides.mathtext/matharray/) | Anger en vertikal samling av ekvationer eller valfri matematiska objekt |
| [`MathArrayFactory`](/slides/python-net/sv/aspose.slides.mathtext/matharrayfactory/) | Tillåter att skapa en math array |
| [`MathBar`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/) | Anger bar-funktionen, bestående av ett basargument och ett över- eller understreck |
| [`MathBarFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathbarfactory/) | Tillåter att skapa ett math bar |
| [`MathBlock`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/) | Anger en instans av matematisk text som finns inom ett MathParagraph och börjar på en egen rad.<br/>            Alla matematiska zoner, inklusive ekvationer, uttryck, samlingar av ekvationer eller uttryck, och formler representeras av ett math block. |
| [`MathBlockFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathblockfactory/) | Tillåter att skapa ett math block |
| [`MathBorderBox`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/) | Ritar en rektangulär eller annan kant runt IMathElement. |
| [`MathBorderBoxFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathborderboxfactory/) | Tillåter att skapa en math border box |
| [`MathBox`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/) | Anger den logiska inramningen (paketeringen) av ett matematiskt element.<br/>            Till exempel kan ett inramat objekt fungera som en operatoremulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytning, eller grupperas så att radbrytningar inte tillåts inom.<br/>            Till exempel bör operatorn \"==\" inramas för att förhindra radbrytningar. |
| [`MathBoxFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathboxfactory/) | Tillåter att skapa en math box |
| [`MathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/) | Anger delimitatorobjektet, bestående av öppnings- och stängningstecken (såsom parenteser, <br/>            klammerparenteser, hakparenteser och vertikala streck), och ett eller flera matematiska element inuti, separerade av ett specificerat tecken.<br/>            Exempel: (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiterfactory/) | Tillåter att skapa en math delimiter |
| [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/) | Bas klass för IMathElement med implementation av vissa metoder som är gemensamma för alla ärvda klasser<br/>            Endast för internt bruk. Ärvd klass måste vara IMathElement. |
| [`MathFraction`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/) | Anger bråkobjektet, bestående av en täljare och en nämnare separerade av en bråkstreck.<br/>            Bråkstrecket kan vara horisontellt eller diagonalt, beroende på bråkets egenskaper.<br/>            Bråkobjektet används även för att representera stack-funktionen, som placerar ett element ovanpå ett annat, utan bråkstreck. |
| [`MathFractionFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathfractionfactory/) | Tillåter att skapa ett math bråk |
| [`MathFunction`](/slides/python-net/sv/aspose.slides.mathtext/mathfunction/) | Anger en funktion av ett argument. |
| [`MathFunctionFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathfunctionfactory/) | Tillåter att skapa en math funktion |
| [`MathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/) | Anger ett grupperingstegn ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan element |
| [`MathGroupingCharacterFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacterfactory/) | Tillåter att skapa ett math grupperingstecken |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | Anger Sub-Superscript-objektet, som består av en bas <br/>            och en nedsänkt och upphöjd index placerad till vänster om basen. |
| [`MathLimit`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/) | Anger Limit-objektet, bestående av text på baslinjen och förminskad text omedelbart ovanför eller nedanför den. |
| [`MathLimitFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathlimitfactory/) | Tillåter att skapa IMathLimit |
| [`MathMatrix`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/) | Anger Matrix-objektet, bestående av underordnade element arrangerade i en eller flera rader och kolumner. <br/>            Det är viktigt att notera att matriser inte har inbyggda delimitatorer. <br/>            För att placera matrisen i hakparenteserna bör du använda delimitatorobjektet (IMathDelimiter).<br/>            Null-argument kan användas för att skapa luckor i matriser. |
| [`MathMatrixFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrixfactory/) | Tillåter att skapa en math matris |
| [`MathNaryOperator`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/) | Anger ett N-ärt matematiskt objekt, såsom Summation och Integral.<br/>            Det består av en operator, en bas (eller operand), och valfria övre och nedre gränser. <br/>            Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral |
| [`MathNaryOperatorFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperatorfactory/) | Tillåter att skapa IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/sv/aspose.slides.mathtext/mathparagraph/) | Matematisk paragraf som är en behållare för matematiska block (IMathBlock) |
| [`MathParagraphFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathparagraphfactory/) | Tillåter att skapa en math paragraf |
| [`MathPhantom`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/) | Representerar ett phantom math-objekt (<m:phant>) som påverkar layouten för dess underordnade element<br/>            utan nödvändigtvis att visas. Ett phantom kan dölja dess basuttryck samtidigt som det bevarar<br/>            dess bredd, höjd eller djup för att justera formler eller reservera utrymme. <br/>            Synlighet och geometribeteende styrs av egenskaper som Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc och Transp. |
| [`MathPortion`](/slides/python-net/sv/aspose.slides.mathtext/mathportion/) | Representerar en del med matematisk kontext inuti. |
| [`MathRadical`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/) | Anger radikalfunktionen, bestående av en bas och en valfri grad.<br/>            Exempel på radikalobjekt är √𝑥. |
| [`MathRadicalFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathradicalfactory/) | Tillåter att skapa en math radikal |
| [`MathRightSubSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | Anger Sub-Superscript-objektet, som består av en bas <br/>            och en nedsänkt och upphöjd index placerad till höger om basen. |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | Tillåter att skapa IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/) | Anger subscript-objektet, som består av en bas <br/>            och en förminskad subscript placerad nedanför och till höger. |
| [`MathSubscriptElementFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelementfactory/) | Tillåter att skapa IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/) | Anger superscript-objektet, som består av en bas <br/>            och en förminskad superscript placerad ovanför och till höger |
| [`MathSuperscriptElementFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelementfactory/) | Tillåter att skapa IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/) | Matematisk text |
| [`MathematicalTextFactory`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltextfactory/) | Tillåter att skapa ett MathematicalText-element |

## Uppräkningar

| Uppräkning | Beskrivning |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimitershape/) | Placeringen och storleken på delimitatorerna i förhållande till innehållet i operanderna |
| [`MathFractionTypes`](/slides/python-net/sv/aspose.slides.mathtext/mathfractiontypes/) | Bråktstyper |
| [`MathFunctionsOfOneArgument`](/slides/python-net/sv/aspose.slides.mathtext/mathfunctionsofoneargument/) | Vanliga matematiska funktioner med ett argument |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/sv/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | Vanliga matematiska funktioner med två argument |
| [`MathHorizontalAlignment`](/slides/python-net/sv/aspose.slides.mathtext/mathhorizontalalignment/) | Horisontell justering |
| [`MathIntegralTypes`](/slides/python-net/sv/aspose.slides.mathtext/mathintegraltypes/) | Matematiska integraltyper |
| [`MathJustification`](/slides/python-net/sv/aspose.slides.mathtext/mathjustification/) | Anger justering av math-paragrafen (en serie av intilliggande instanser av matematisk text inom samma paragraf) |
| [`MathLimitLocations`](/slides/python-net/sv/aspose.slides.mathtext/mathlimitlocations/) | Placering av gränser (subscript/superscript) i n-ära operatorer. |
| [`MathNaryOperatorTypes`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperatortypes/) | Nära operator IMathNaryOperator-typer (exklusive integraler)<br/>            För integraler [`MathIntegralTypes`](/slides/python-net/sv/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/sv/aspose.slides.mathtext/mathrowspacingrule/) | Typen av vertikal avstånd mellan kolumner i en matris eller array |
| [`MathSpacingRules`](/slides/python-net/sv/aspose.slides.mathtext/mathspacingrules/) | Typer av mellanrum (horisontellt avstånd) mellan kolumner i en matris |
| [`MathTopBotPositions`](/slides/python-net/sv/aspose.slides.mathtext/mathtopbotpositions/) | Uppräkning av topp/botten-positioner |
| [`MathVerticalAlignment`](/slides/python-net/sv/aspose.slides.mathtext/mathverticalalignment/) | Vertikal justering |