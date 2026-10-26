---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 157
url: /sv/aspose.slides.mathtext/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BaseScript](./basescript/) | Mattskript |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) med [Control](../aspose.slides/control/) Teckenegenskaper |
| [IMathAccent](./imathaccent/) | Specificerar accentfunktionen, bestående av en bas och ett kombinerat diakritiskt tecken Exempel: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Tillåter att skapa en matematikaccent |
| [IMathArray](./imatharray/) | Specificerar en vertikal matris av ekvationer eller valfria matematiska objekt |
| [IMathArrayFactory](./imatharrayfactory/) | Tillåter att skapa en matris |
| [IMathBar](./imathbar/) | Specificerar bar-funktionen, bestående av ett basargument och ett överstreck eller understreck |
| [IMathBarFactory](./imathbarfactory/) | Tillåter att skapa ett matematiskt streck |
| [IMathBlock](./imathblock/) | Specificerar en instans av matematisk text som finns inom en [MathParagraph](./mathparagraph/) och börjar på en egen rad. Alla matematiska zoner, inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck samt formler, representeras av ett math block. |
| [IMathBlockCollection](./imathblockcollection/) | Samling av math block ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Tillåter att skapa ett math block |
| [IMathBorderBox](./imathborderbox/) | Ritar en rektangulär eller annan ram runt [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Tillåter att skapa en math border box |
| [IMathBox](./imathbox/) | Specificerar den logiska inramningen (paketeringen) av ett matematisk element. Till exempel kan ett inramat objekt fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytning, eller grupperas så att radbrytningar inte tillåts inom det. Till exempel bör operatorn "==" inramas för att förhindra radbrytningar. |
| [IMathBoxFactory](./imathboxfactory/) | Tillåter att skapa en math-box |
| [IMathDelimiter](./imathdelimiter/) | Specificerar avgränsare-objektet, bestående av öppnings- och stängningstecken (såsom parenteser, klammerparenteser, hakparenteser och vertikala streck), samt ett eller flera matematiska element inuti, separerade av ett specificerat tecken. Exempel: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Tillåter att skapa en math-avgränsare |
| [IMathElement](./imathelement/) | Basgränssnitt för alla matematiska element: bråk, matematisk text, funktion, uttryck med flera element osv |
| [IMathElementCollection](./imathelementcollection/) | Representerar en samling av matematiska element (MathElement). |
| [IMathematicalText](./imathematicaltext/) | Matematisk text |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Tillåter att skapa ett [MathematicalText](./mathematicaltext/)-element |
| [IMathFraction](./imathfraction/) | Specificerar bråk-objektet, bestående av en täljare och en nämnare separerade av ett bråkstreck. Bråkstrecket kan vara horisontellt eller diagonalt, beroende på bråkegenskaperna. Bråk-objektet används också för att representera stack-funktionen, som placerar ett element ovanför ett annat utan bråkstreck. |
| [IMathFractionFactory](./imathfractionfactory/) | Tillåter att skapa ett matematiskt bråk |
| [IMathFunction](./imathfunction/) | Specificerar en funktion av ett argument. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Tillåter att skapa en matematisk funktion |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Specificerar en grupperingstegn ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan element |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Tillåter att skapa ett math-grupperingstecken |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Specificerar Sub-Superscript-objektet, som består av en bas samt nedsänkt och upphöjd index placerade till vänster om basen. |
| [IMathLimit](./imathlimit/) | Specificerar Limit-objektet, bestående av text på baslinjen och förminskad text omedelbart ovanför eller under den. |
| [IMathLimitFactory](./imathlimitfactory/) | Tillåter att skapa [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Specificerar Matrix-objektet, bestående av underordnade element ordnade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteserna bör du använda avgränsare-objektet ([IMathDelimiter](./imathdelimiter/)). Noll-argument kan användas för att skapa luckor i matriser. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Tillåter att skapa en math-matris |
| [IMathNaryOperator](./imathnaryoperator/) | Specificerar ett N-ärt matematiskt objekt, såsom Summation och Integral. Det består av en operator, en bas (eller operand) och valfria övre och undre gränser. Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral. |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Tillåter att skapa [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Specificerar egenskaperna för [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Matematisk paragraf som är en behållare för matematiska block ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Tillåter att skapa ett math-paragraf |
| [IMathPhantom](./imathphantom/) | Representerar ett phantom-math-objekt (<m:phant>) som påverkar layouten för dess underordnade element utan att nödvändigtvis visa det. Ett phantom kan dölja sitt basuttryck samtidigt som bredd, höjd eller djup bevaras för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper såsom Show, ZeroWid, ZeroAsc, ZeroDesc och Transp. |
| [IMathPortion](./imathportion/) | Representerar en del med matematisk kontext inuti. |
| [IMathRadical](./imathradical/) | Specificerar radikal-funktionen, bestående av en bas och en valfri grad. Exempel på radikal-objekt är \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Tillåter att skapa ett math-radikal |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Specificerar Sub-Superscript-objektet, som består av en bas samt nedsänkt och upphöjd index placerade till höger om basen. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Tillåter att skapa [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Specificerar subscript-objektet, som består av en bas och en förminskad subscript placerad under och till höger. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Tillåter att skapa [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Specificerar superscript-objektet, som består av en bas och en förminskad superscript placerad ovanför och till höger. |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Tillåter att skapa [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Specificerar accentfunktionen, bestående av en bas och ett kombinerat diakritiskt tecken Exempel: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Tillåter att skapa en math-accent |
| [MathArray](./matharray/) | Specificerar en vertikal matris av ekvationer eller valfria matematiska objekt. |
| [MathArrayFactory](./matharrayfactory/) | Tillåter att skapa en math-matris |
| [MathBar](./mathbar/) | Specificerar bar-funktionen, bestående av ett basargument och ett överstreck eller understreck |
| [MathBarFactory](./mathbarfactory/) | Tillåter att skapa ett math-streck |
| [MathBlock](./mathblock/) | Specificerar en instans av matematisk text som finns inom en [MathParagraph](./mathparagraph/) och börjar på en egen rad. Alla matematiska zoner, inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck samt formler, representeras av ett math block. |
| [MathBlockFactory](./mathblockfactory/) | Tillåter att skapa ett math block |
| [MathBorderBox](./mathborderbox/) | Ritar en rektangulär eller annan ram runt [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Tillåter att skapa en math border box |
| [MathBox](./mathbox/) | Specificerar den logiska inramningen (paketeringen) av ett matematisk element. Till exempel kan ett inramat objekt fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytning, eller grupperas så att radbrytningar inte tillåts inom det. Till exempel bör operatorn "==" inramas för att förhindra radbrytningar. |
| [MathBoxFactory](./mathboxfactory/) | Tillåter att skapa en math-box |
| [MathDelimiter](./mathdelimiter/) | Specificerar avgränsare-objektet, bestående av öppnings- och stängningstecken (såsom parenteser, klammerparenteser, hakparenteser och vertikala streck), samt ett eller flera matematiska element inuti, separerade av ett specificerat tecken. Exempel: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Tillåter att skapa en math-avgränsare |
| [MathElementBase](./mathelementbase/) | Bas-klass för [IMathElement](./imathelement/) med implementeringen av vissa metoder som är gemensamma för alla ärvda klasser. Endast för internt bruk. Ärvd klass måste vara [IMathElement](./imathelement/). |
| [MathematicalText](./mathematicaltext/) | Matematisk text |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Tillåter att skapa ett [MathematicalText](./mathematicaltext/)-element |
| [MathFraction](./mathfraction/) | Specificerar bråk-objektet, bestående av en täljare och en nämnare separerade av ett bråkstreck. Bråkstrecket kan vara horisontellt eller diagonalt, beroende på bråkegenskaperna. Bråk-objektet används också för att representera stack-funktionen, som placerar ett element ovanför ett annat utan bråkstreck. |
| [MathFractionFactory](./mathfractionfactory/) | Tillåter att skapa ett math-bråk |
| [MathFunction](./mathfunction/) | Specificerar en funktion av ett argument. |
| [MathFunctionFactory](./mathfunctionfactory/) | Tillåter att skapa en matematisk funktion |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Specificerar en grupperingstegn ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan element |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Tillåter att skapa ett math-grupperingstecken |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Specificerar Sub-Superscript-objektet, som består av en bas samt nedsänkt och upphöjd index placerade till vänster om basen. |
| [MathLimit](./mathlimit/) | Specificerar Limit-objektet, bestående av text på baslinjen och förminskad text omedelbart ovanför eller under den. |
| [MathLimitFactory](./mathlimitfactory/) | Tillåter att skapa [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Specificerar Matrix-objektet, bestående av underordnade element ordnade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteserna bör du använda avgränsare-objektet ([IMathDelimiter](./imathdelimiter/)). Noll-argument kan användas för att skapa luckor i matriser. |
| [MathMatrixFactory](./mathmatrixfactory/) | Tillåter att skapa en math-matris |
| [MathNaryOperator](./mathnaryoperator/) | Specificerar ett N-ärt matematiskt objekt, såsom Summation och Integral. Det består av en operator, en bas (eller operand) och valfria övre och undre gränser. Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral. |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Tillåter att skapa [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Matematisk paragraf som är en behållare för matematiska block ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Tillåter att skapa ett math-paragraf |
| [MathPhantom](./mathphantom/) | Representerar ett phantom-math-objekt (<m:phant>) som påverkar layouten för dess underordnade element utan att nödvändigtvis visa det. Ett phantom kan dölja sitt basuttryck samtidigt som bredd, höjd eller djup bevaras för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper såsom Show, ZeroWid, ZeroAsc, ZeroDesc och Transp. |
| [MathPortion](./mathportion/) | Representerar en del med matematisk kontext inuti. |
| [MathRadical](./mathradical/) | Specificerar radikal-funktionen, bestående av en bas och en valfri grad. Exempel på radikal-objekt är \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Tillåter att skapa ett math-radikal |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Specificerar Sub-Superscript-objektet, som består av en bas samt nedsänkt och upphöjd index placerade till höger om basen. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Tillåter att skapa [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Specificerar subscript-objektet, som består av en bas och en förminskad subscript placerad under och till höger. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Tillåter att skapa [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Specificerar superscript-objektet, som består av en bas och en förminskad superscript placerad ovanför och till höger |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Tillåter att skapa [IMathSuperscriptElement](./imathsuperscriptelement/) |

## Enum-typer

| Enum | Beskrivning |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | Placeringen och storleken på avgränsarna i förhållande till operanderna |
| [MathFractionTypes](./mathfractiontypes/) | Bråktyper |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Vanliga matematiska funktioner med ett argument |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Vanliga matematiska funktioner med två argument |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Horisontell justering |
| [MathIntegralTypes](./mathintegraltypes/) | Matematiska integraltyper |
| [MathJustification](./mathjustification/) | Specificerar justering av math-paragrafen (en serie av intilliggande instanser av matematisk text inom samma paragraf) |
| [MathLimitLocations](./mathlimitlocations/) | Placering av gränser (subscript/superscript) i n-ära operatorer. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | N-ära operator [IMathNaryOperator](./imathnaryoperator/) typer (exklusive integraler) För integraler [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | Typen av vertikalt avstånd mellan kolumner i en matris eller array |
| [MathSpacingRules](./mathspacingrules/) | Typer av mellanrum (horisontellt avstånd) mellan kolumner i en matris |
| [MathTopBotPositions](./mathtopbotpositions/) | Uppräkning av topp/botten-positioner |
| [MathVerticalAlignment](./mathverticalalignment/) | Vertikal justering |