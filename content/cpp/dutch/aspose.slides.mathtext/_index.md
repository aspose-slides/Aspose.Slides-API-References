---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides voor C++ API Referentie
description: 
type: docs
weight: 157
url: /nl/aspose.slides.mathtext/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [BaseScript](./basescript/) | Math script |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) with [Control](../aspose.slides/control/) Karaktereigenschappen |
| [IMathAccent](./imathaccent/) | Specificeert de accentfunctie, bestaande uit een basis en een combinerend diakritisch teken Voorbeeld: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Staat toe een wiskundig accent te maken |
| [IMathArray](./imatharray/) | Specificeert een verticale array van vergelijkingen of willekeurige wiskundige objecten |
| [IMathArrayFactory](./imatharrayfactory/) | Staat toe een wiskundige array te maken |
| [IMathBar](./imathbar/) | Specificeert de balkfunctie, bestaande uit een basisargument en een bovenbalk of onderbalk |
| [IMathBarFactory](./imathbarfactory/) | Staat toe een wiskundige balk te maken |
| [IMathBlock](./imathblock/) | Specificeert een instantie van wiskundige tekst die binnen een [MathParagraph](./mathparagraph/) staat en op een eigen regel begint. Alle wiskundige zones, inclusief vergelijkingen, expressies, arrays van vergelijkingen of expressies, en formules worden weergegeven door een wiskundig blok. |
| [IMathBlockCollection](./imathblockcollection/) | Collectie van wiskundige blokken ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Staat toe een wiskundig blok te maken |
| [IMathBorderBox](./imathborderbox/) | Tekent een rechthoekige of andere rand rond de [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Staat toe een wiskundige randvak te maken |
| [IMathBox](./imathbox/) | Specificeert de logische verpakking van een wiskundig element. Bijvoorbeeld, een verpakt object kan dienen als een operatoremulator met of zonder een uitlijningspunt, dienen als een regeleinde punt, of gegroepeerd worden zodat geen regeleindes binnen toegestaan zijn. Bijvoorbeeld, de \"==\" operator moet verpakt worden om regeleindes te voorkomen. |
| [IMathBoxFactory](./imathboxfactory/) | Staat toe een wiskundige box te maken |
| [IMathDelimiter](./imathdelimiter/) | Specificeert het scheidingstekenobject, bestaande uit opening- en sluittekens (zoals haakjes, accolades, vierkante haken en verticale strepen), en een of meer wiskundige elementen erin, gescheiden door een opgegeven teken. Voorbeelden: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Staat toe een wiskundig scheidingsteken te maken |
| [IMathElement](./imathelement/) | Basisinterface van elk wiskundig element: breuk, wiskundige tekst, functie, expressie met meerdere elementen enz. |
| [IMathElementCollection](./imathelementcollection/) | Stelt een collectie van wiskundige elementen (MathElement) voor. |
| [IMathematicalText](./imathematicaltext/) | Wiskundige tekst |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Staat toe een [MathematicalText](./mathematicaltext/) element te maken |
| [IMathFraction](./imathfraction/) | Specificeert het breukobject, bestaande uit een teller en een noemer gescheiden door een breukstreep. De breukstreep kan horizontaal of diagonaal zijn, afhankelijk van de breukeigenschappen. Het breukobject wordt ook gebruikt om de stapelfunctie weer te geven, die één element boven een ander plaatst, zonder breukstreep. |
| [IMathFractionFactory](./imathfractionfactory/) | Staat toe een wiskundige breuk te maken |
| [IMathFunction](./imathfunction/) | Specificeert een functie van een argument. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Staat toe een wiskundige functie te maken |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Specificeert een groepsymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken. |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Staat toe een wiskundig groepsymbool te maken |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Specificeert het Sub-Superscript-object, dat bestaat uit een basis en een subscript en superscript die links van de basis staan. |
| [IMathLimit](./imathlimit/) | Specificeert het Limiet-object, bestaande uit tekst op de basislijn en verkleinde tekst direct erboven of eronder. |
| [IMathLimitFactory](./imathlimitfactory/) | Staat toe [IMathLimit](./imathlimit/) te maken |
| [IMathMatrix](./imathmatrix/) | Specificeert het Matrix-object, bestaande uit kind-elementen gerangschikt in één of meer rijen en kolommen. Het is belangrijk op te merken dat matrices geen ingebouwde scheidingstekens hebben. Om de matrix in de haakjes te plaatsen, moet je het scheidingstekenobject ([IMathDelimiter](./imathdelimiter/)) gebruiken. Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Staat toe een wiskundige matrix te maken |
| [IMathNaryOperator](./imathnaryoperator/) | Specificeert een N-air wiskundig object, zoals Sommaties en Integralen. Het bestaat uit een operator, een basis (of operand), en optionele boven- en onderlimieten. Voorbeelden van N-air operators zijn: Sommaties, Vereniging, Doorsnede, Integralen. |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Staat toe [IMathNaryOperator](./imathnaryoperator/) te maken |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Specificeert eigenschappen van [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Wiskundige alinea die een container is voor wiskundige blokken ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Staat toe een wiskundige alinea te maken |
| [IMathPhantom](./imathphantom/) | Stelt een phantom-wiskundig object (<m:phant>) voor dat de lay-out van het kind-element beïnvloedt zonder het noodzakelijkerwijs weer te geven. Een phantom kan zijn basisexpressie verbergen terwijl de breedte, hoogte of diepte behouden blijft om formules uit te lijnen of ruimte te reserveren. Zichtbaarheid en geometrie-gedrag worden bestuurd door eigenschappen zoals Show, ZeroWid, ZeroAsc, ZeroDesc en Transp. |
| [IMathPortion](./imathportion/) | Stelt een gedeelte met wiskundige context binnenin voor. |
| [IMathRadical](./imathradical/) | Specificeert de radicale functie, bestaande uit een basis en een optionele graad. Voorbeeld van een radical object is \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Staat toe een wiskundige radical te maken |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Specificeert het Sub-Superscript-object, dat bestaat uit een basis en een subscript en superscript die rechts van de basis staan. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Staat toe [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) te maken |
| [IMathSubscriptElement](./imathsubscriptelement/) | Specificeert het subscript-object, dat bestaat uit een basis en een verkleind subscript dat onder en rechts van de basis staat. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Staat toe [IMathSubscriptElement](./imathsubscriptelement/) te maken |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Specificeert het superscript-object, dat bestaat uit een basis en een verkleinde superscript die boven en rechts van de basis staat. |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Staat toe [IMathSuperscriptElement](./imathsuperscriptelement/) te maken |
| [MathAccent](./mathaccent/) | Specificeert de accentfunctie, bestaande uit een basis en een combinerend diakritisch teken Voorbeeld: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Staat toe een wiskundig accent te maken |
| [MathArray](./matharray/) | Specificeert een verticale array van vergelijkingen of willekeurige wiskundige objecten |
| [MathArrayFactory](./matharrayfactory/) | Staat toe een wiskundige array te maken |
| [MathBar](./mathbar/) | Specificeert de balkfunctie, bestaande uit een basisargument en een bovenbalk of onderbalk. |
| [MathBarFactory](./mathbarfactory/) | Staat toe een wiskundige balk te maken |
| [MathBlock](./mathblock/) | Specificeert een instantie van wiskundige tekst die zich binnen een [MathParagraph](./mathparagraph/) bevindt en op een eigen regel begint. Alle wiskundige zones, inclusief vergelijkingen, expressies, arrays van vergelijkingen of expressies, en formules worden weergegeven door een wiskundig blok. |
| [MathBlockFactory](./mathblockfactory/) | Staat toe een wiskundig blok te maken |
| [MathBorderBox](./mathborderbox/) | Tekent een rechthoekige of andere rand rond de [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Staat toe een wiskundige randvak te maken |
| [MathBox](./mathbox/) | Specificeert de logische verpakking van een wiskundig element. Bijvoorbeeld, een verpakt object kan dienen als een operatoremulator met of zonder een uitlijningspunt, dienen als een regeleinde punt, of gegroepeerd worden zodat geen regeleindes binnen toegestaan zijn. Bijvoorbeeld, de \"==\" operator moet verpakt worden om regeleindes te voorkomen. |
| [MathBoxFactory](./mathboxfactory/) | Staat toe een wiskundige box te maken |
| [MathDelimiter](./mathdelimiter/) | Specificeert het scheidingstekenobject, bestaande uit opening- en sluittekens (zoals haakjes, accolades, vierkante haken en verticale strepen), en een of meer wiskundige elementen erin, gescheiden door een opgegeven teken. Voorbeelden: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Staat toe een wiskundig scheidingsteken te maken |
| [MathElementBase](./mathelementbase/) | Basisklasse voor [IMathElement](./imathelement/) met de implementatie van enkele methoden die gemeenschappelijk zijn voor alle geërfde klassen. Alleen intern gebruik. Geërfde klasse moet [IMathElement](./imathelement/) zijn. |
| [MathematicalText](./mathematicaltext/) | Wiskundige tekst |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Staat toe een [MathematicalText](./mathematicaltext/) element te maken |
| [MathFraction](./mathfraction/) | Specificeert het breukobject, bestaande uit een teller en een noemer gescheiden door een breukstreep. De breukstreep kan horizontaal of diagonaal zijn, afhankelijk van de breukeigenschappen. Het breukobject wordt ook gebruikt om de stapelfunctie weer te geven, die één element boven een ander plaatst, zonder breukstreep. |
| [MathFractionFactory](./mathfractionfactory/) | Staat toe een wiskundige breuk te maken |
| [MathFunction](./mathfunction/) | Specificeert een functie van een argument. |
| [MathFunctionFactory](./mathfunctionfactory/) | Staat toe een wiskundige functie te maken |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Specificeert een groepsymbool boven of onder een expressie, meestal om de relatie tussen elementen te benadrukken. |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Staat toe een wiskundig groepsymbool te maken |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Specificeert het Sub-Superscript-object, dat bestaat uit een basis en een subscript en superscript die links van de basis staan. |
| [MathLimit](./mathlimit/) | Specificeert het Limiet-object, bestaande uit tekst op de basislijn en verkleinde tekst direct erboven of eronder. |
| [MathLimitFactory](./mathlimitfactory/) | Staat toe [IMathLimit](./imathlimit/) te maken |
| [MathMatrix](./mathmatrix/) | Specificeert het Matrix-object, bestaande uit kind-elementen gerangschikt in één of meer rijen en kolommen. Het is belangrijk op te merken dat matrices geen ingebouwde scheidingstekens hebben. Om de matrix in de haakjes te plaatsen, moet je het scheidingstekenobject ([IMathDelimiter](./imathdelimiter/)) gebruiken. Null-argumenten kunnen worden gebruikt om gaten in matrices te creëren. |
| [MathMatrixFactory](./mathmatrixfactory/) | Staat toe een wiskundige matrix te maken |
| [MathNaryOperator](./mathnaryoperator/) | Specificeert een N-air wiskundig object, zoals Sommaties en Integralen. Het bestaat uit een operator, een basis (of operand), en optionele boven- en onderlimieten. Voorbeelden van N-air operators zijn: Sommaties, Vereniging, Doorsnede, Integralen. |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Staat toe [IMathNaryOperator](./imathnaryoperator/) te maken |
| [MathParagraph](./mathparagraph/) | Wiskundige alinea die een container is voor wiskundige blokken ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Staat toe een wiskundige alinea te maken |
| [MathPhantom](./mathphantom/) | Stelt een phantom-wiskundig object (<m:phant>) voor dat de lay-out van het kind-element beïnvloedt zonder het noodzakelijkerwijs weer te geven. Een phantom kan zijn basisexpressie verbergen terwijl de breedte, hoogte of diepte behouden blijft om formules uit te lijnen of ruimte te reserveren. Zichtbaarheid en geometrie-gedrag worden bestuurd door eigenschappen zoals Show, ZeroWid, ZeroAsc, ZeroDesc en Transp. |
| [MathPortion](./mathportion/) | Stelt een gedeelte met wiskundige context binnenin voor. |
| [MathRadical](./mathradical/) | Specificeert de radicale functie, bestaande uit een basis en een optionele graad. Voorbeeld van een radical object is \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Staat toe een wiskundige radical te maken |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Specificeert het Sub-Superscript-object, dat bestaat uit een basis en een subscript en superscript die rechts van de basis staan. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Staat toe [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) te maken |
| [MathSubscriptElement](./mathsubscriptelement/) | Specificeert het subscript-object, dat bestaat uit een basis en een verkleind subscript dat onder en rechts van de basis staat. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Staat toe [IMathSubscriptElement](./imathsubscriptelement/) te maken |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Specificeert het superscript-object, dat bestaat uit een basis en een verkleinde superscript die boven en rechts van de basis staat |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Staat toe [IMathSuperscriptElement](./imathsuperscriptelement/) te maken |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | De locatie en grootte van de scheidingstekens ten opzichte van de inhoud van de operanden |
| [MathFractionTypes](./mathfractiontypes/) | Breuktypen |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Veelvoorkomende wiskundige functies met één argument |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Veelvoorkomende wiskundige functies met twee argumenten |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Horizontale uitlijning |
| [MathIntegralTypes](./mathintegraltypes/) | Wiskundige integraaltypen |
| [MathJustification](./mathjustification/) | Specificeert de uitlijning van de wiskundige alinea (een reeks van aangrenzende instanties van wiskundige tekst binnen dezelfde alinea) |
| [MathLimitLocations](./mathlimitlocations/) | Locatie van limieten (subscript/superscript) in n-air operators. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | N-air operator [IMathNaryOperator](./imathnaryoperator/) typen (exclusief integralen) Voor integralen [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | Het type verticale spatiëring tussen kolommen in een matrix of array |
| [MathSpacingRules](./mathspacingrules/) | Typen van gat (horizontale spatiëring) tussen kolommen van een matrix |
| [MathTopBotPositions](./mathtopbotpositions/) | Enumeratie van boven/onder posities |
| [MathVerticalAlignment](./mathverticalalignment/) | Verticale uitlijning |