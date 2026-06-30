---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes för .NET API-referens
description: Innehåller klasser för arbete med matematisk text i Microsoft PowerPoint-presentationer.
type: docs
weight: 140
url: /sv/aspose.slides.mathtext/
---
Innehåller klasser för arbete med matematisk text i Microsoft PowerPoint-presentationer.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BaseScript](./basescript) | Matematikskript |
| [MathAccent](./mathaccent) | Anger accentfunktionen, bestående av en bas och ett kombinerande diakritiskt tecken. Exempel: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Tillåter att skapa en matematisk accent |
| [MathArray](./matharray) | Anger en vertikal matris av ekvationer eller andra matematiska objekt |
| [MathArrayFactory](./matharrayfactory) | Tillåter att skapa en matematisk matris |
| [MathBar](./mathbar) | Anger bar-funktionen, bestående av ett basargument och en över- eller underlinje |
| [MathBarFactory](./mathbarfactory) | Tillåter att skapa en matematisk bar |
| [MathBlock](./mathblock) | Anger en instans av matematisk text som finns i ett MathParagraph och startar på en egen rad. Alla matematiska områden, inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck samt formler, representeras av ett math-block. |
| [MathBlockFactory](./mathblockfactory) | Tillåter att skapa ett math-block |
| [MathBorderBox](./mathborderbox) | Ritar en rektangulär eller annan ram runt IMathElement. |
| [MathBorderBoxFactory](./mathborderboxfactory) | Tillåter att skapa en math-ramruta |
| [MathBox](./mathbox) | Anger den logiska inramningen (paketeringen) av ett matematiskt element. Till exempel kan ett inramat objekt fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytning, eller grupperas så att radbrytningar inte tillåts inom. Till exempel bör "=="-operatorn inramas för att förhindra radbrytningar. |
| [MathBoxFactory](./mathboxfactory) | Tillåter att skapa en math-box |
| [MathDelimiter](./mathdelimiter) | Anger delimiter-objektet, bestående av öppnings- och stängningstecken (såsom parenteser, klammer, hakparenteser och vertikala staplar) samt ett eller flera matematiska element inuti, separerade av ett angivet tecken. Exempel: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Tillåter att skapa ett math-delimiter |
| [MathElementBase](./mathelementbase) | Bas-klass för IMathElement med implementation av vissa metoder som är gemensamma för alla ärvda klasser. Endast för internt bruk. Ärvd klass måste vara IMathElement. |
| [MathematicalText](./mathematicaltext) | Matematisk text |
| [MathematicalTextFactory](./mathematicaltextfactory) | Tillåter att skapa ett MathematicalText-element |
| [MathFraction](./mathfraction) | Anger bråkelementet, bestående av en täljare och nämnare separerade av en bråklinje. Bråklinjen kan vara horisontell eller diagonal, beroende på bråkegenskaperna. Bråkelementet används även för att representera stack-funktionen, som placerar ett element ovanpå ett annat utan bråklinje. |
| [MathFractionFactory](./mathfractionfactory) | Tillåter att skapa ett matematiskt bråk |
| [MathFunction](./mathfunction) | Anger en funktion av ett argument. |
| [MathFunctionFactory](./mathfunctionfactory) | Tillåter att skapa en matematisk funktion |
| [MathGroupingCharacter](./mathgroupingcharacter) | Anger en gruppsymbol ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan element. |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Tillåter att skapa ett math-grupptecken |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Anger Sub-Superskript-objektet, som består av en bas samt en nedsänkt och upphöjd skript placerade till vänster om basen. |
| [MathLimit](./mathlimit) | Anger Limit-objektet, bestående av text på baslinjen och förminskad text omedelbart ovanför eller nedanför. |
| [MathLimitFactory](./mathlimitfactory) | Tillåter att skapa IMathLimit |
| [MathMatrix](./mathmatrix) | Anger Matrix-objektet, bestående av underordnade element arrangerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda delimitrar. För att placera matrisen i hakparenteser bör du använda delimiter-objektet (IMathDelimiter). Null-argument kan användas för att skapa luckor i matriser. |
| [MathMatrixFactory](./mathmatrixfactory) | Tillåter att skapa en matris |
| [MathNaryOperator](./mathnaryoperator) | Anger ett N-ärt matematiskt objekt, så som Summation och Integral. Det består av en operator, en bas (eller operand) samt valfria övre och nedre gränser. Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral. |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Tillåter att skapa IMathNaryOperator |
| [MathParagraph](./mathparagraph) | Matematisk paragraf som är en behållare för matematiska block (IMathBlock) |
| [MathParagraphFactory](./mathparagraphfactory) | Tillåter att skapa en matematisk paragraf |
| [MathPhantom](./mathphantom) | Representerar ett phantom-math-objekt (&lt;m:phant&gt;) som påverkar layouten för dess underordnade element utan nödvändigtvis att visas. Ett phantom kan dölja dess basuttryck medan bredd, höjd eller djup bevaras för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper som Show, ZeroWid, ZeroAsc, ZeroDesc och Transp. |
| [MathPortion](./mathportion) | Representerar en del med matematisk kontext inuti. |
| [MathRadical](./mathradical) | Anger radikal-funktionen, bestående av en bas och en valfri grad. Exempel på ett radikalobjekt är √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Tillåter att skapa ett math-radikal |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Anger Sub-Superskript-objektet, som består av en bas samt en nedsänkt och upphöjd skript placerade till höger om basen. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Tillåter att skapa IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | Anger nedsänkt skript-objekt, som består av en bas och ett förminskat nedsänkt skript placerat nedanför och till höger. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Tillåter att skapa IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | Anger upphöjt skript-objekt, som består av en bas och ett förminskat upphöjt skript placerat ovanför och till höger |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Tillåter att skapa IMathSuperscriptElement |

## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IMathAccent](./imathaccent) | Anger accentfunktionen, bestående av en bas och ett kombinerande diakritiskt tecken. Exempel: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Tillåter att skapa en matematisk accent |
| [IMathArray](./imatharray) | Anger en vertikal matris av ekvationer eller andra matematiska objekt |
| [IMathArrayFactory](./imatharrayfactory) | Tillåter att skapa en matematisk matris |
| [IMathBar](./imathbar) | Anger bar-funktionen, bestående av ett basargument och en över- eller underlinje |
| [IMathBarFactory](./imathbarfactory) | Tillåter att skapa en matematisk bar |
| [IMathBlock](./imathblock) | Anger en instans av matematisk text som finns i ett MathParagraph och startar på en egen rad. Alla matematiska områden, inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck samt formler, representeras av ett math-block. |
| [IMathBlockCollection](./imathblockcollection) | Samling av math-block (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | Tillåter att skapa ett math-block |
| [IMathBorderBox](./imathborderbox) | Ritar en rektangulär eller annan ram runt IMathElement. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Tillåter att skapa en math-ramruta |
| [IMathBox](./imathbox) | Anger den logiska inramningen (paketeringen) av ett matematiskt element. Till exempel kan ett inramat objekt fungera som en operator-emulator med eller utan en justeringspunkt, fungera som en radbrytning, eller grupperas så att radbrytningar inte tillåts inom. Till exempel bör "=="-operatorn inramas för att förhindra radbrytningar. |
| [IMathBoxFactory](./imathboxfactory) | Tillåter att skapa en math-box |
| [IMathDelimiter](./imathdelimiter) | Anger delimiter-objektet, bestående av öppnings- och stängningstecken (såsom parenteser, klammer, hakparenteser och vertikala staplar) samt ett eller flera matematiska element inuti, separerade av ett angivet tecken. Exempel: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Tillåter att skapa ett math-delimiter |
| [IMathElement](./imathelement) | Bas-gränssnitt för alla matematiska element: bråk, matematisk text, funktion, uttryck med flera element osv. |
| [IMathElementCollection](./imathelementcollection) | Representerar en samling av matematiska element (MathElement). |
| [IMathematicalText](./imathematicaltext) | Matematisk text |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Tillåter att skapa ett MathematicalText-element |
| [IMathFraction](./imathfraction) | Anger bråkelementet, bestående av en täljare och nämnare separerade av en bråklinje. Bråklinjen kan vara horisontell eller diagonal, beroende på bråkegenskaperna. Bråkelementet används även för att representera stack-funktionen, som placerar ett element ovanpå ett annat utan bråklinje. |
| [IMathFractionFactory](./imathfractionfactory) | Tillåter att skapa ett math-bråk |
| [IMathFunction](./imathfunction) | Anger en funktion av ett argument. |
| [IMathFunctionFactory](./imathfunctionfactory) | Tillåter att skapa en matematisk funktion |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Anger en gruppsymbol ovanför eller under ett uttryck, vanligtvis för att framhäva relationen mellan element. |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Tillåter att skapa ett math-grupptecken |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Anger Sub-Superskript-objektet, som består av en bas samt en nedsänkt och upphöjd skript placerade till vänster om basen. |
| [IMathLimit](./imathlimit) | Anger Limit-objektet, bestående av text på baslinjen och förminskad text omedelbart ovanför eller nedanför. |
| [IMathLimitFactory](./imathlimitfactory) | Tillåter att skapa IMathLimit |
| [IMathMatrix](./imathmatrix) | Anger Matrix-objektet, bestående av underordnade element arrangerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda delimitrar. För att placera matrisen i hakparenteser bör du använda delimiter-objektet (IMathDelimiter). Null-argument kan användas för att skapa luckor i matriser. |
| [IMathMatrixFactory](./imathmatrixfactory) | Tillåter att skapa en matris |
| [IMathNaryOperator](./imathnaryoperator) | Anger ett N-ärt matematiskt objekt, så som Summation och Integral. Det består av en operator, en bas (eller operand) samt valfria övre och nedre gränser. Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral. |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Tillåter att skapa IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Anger egenskaper för IMathNaryOperator |
| [IMathParagraph](./imathparagraph) | Matematisk paragraf som är en behållare för matematiska block (IMathBlock) |
| [IMathParagraphFactory](./imathparagraphfactory) | Tillåter att skapa en matematisk paragraf |
| [IMathPhantom](./imathphantom) | Representerar ett phantom-math-objekt (&lt;m:phant&gt;) som påverkar layouten för dess underordnade element utan nödvändigtvis att visas. Ett phantom kan dölja dess basuttryck medan bredd, höjd eller djup bevaras för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper som Show, ZeroWid, ZeroAsc, ZeroDesc och Transp. |
| [IMathPortion](./imathportion) | Representerar en del med matematisk kontext inuti. |
| [IMathRadical](./imathradical) | Anger radikal-funktionen, bestående av en bas och en valfri grad. Exempel på ett radikalobjekt är √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Tillåter att skapa ett math-radikal |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Anger Sub-Superskript-objektet, som består av en bas samt en nedsänkt och upphöjd skript placerade till höger om basen. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Tillåter att skapa IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | Anger nedsänkt skript-objekt, som består av en bas och ett förminskat nedsänkt skript placerat nedanför och till höger. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Tillåter att skapa IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Anger upphöjt skript-objekt, som består av en bas och ett förminskat upphöjt skript placerat ovanför och till höger |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Tillåter att skapa IMathSuperscriptElement |

## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | Placeringen och storleken på delimitrarna i förhållande till operanderna. |
| [MathFractionTypes](./mathfractiontypes) | Bråktyper |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Vanliga matematiska funktioner med ett argument |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Vanliga matematiska funktioner med två argument |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Horisontell justering |
| [MathIntegralTypes](./mathintegraltypes) | Matematiska integraltyper |
| [MathJustification](./mathjustification) | Anger justering av math-paragrafen (en serie av intilliggande instanser av matematisk text inom samma paragraf). |
| [MathLimitLocations](./mathlimitlocations) | Placering av gränser (nedsänkt/upphöjt) i n-ära operatorer. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | N-ära operator-typer för IMathNaryOperator (exklusive integraler). För integraler [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | Typ av vertikal avstånd mellan kolumner i en matris eller array. |
| [MathSpacingRules](./mathspacingrules) | Typer av luckor (horisontellt avstånd) mellan kolumner i en matris. |
| [MathTopBotPositions](./mathtopbotpositions) | Uppe-/nedre positions-uppräkning |
| [MathVerticalAlignment](./mathverticalalignment) | Vertikal justering |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->