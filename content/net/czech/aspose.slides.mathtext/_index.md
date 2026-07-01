---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes pro .NET API Reference
description: Obsahuje třídy pro práci s matematickým textem v prezentacích Microsoft PowerPoint.
type: docs
weight: 140
url: /cs/aspose.slides.mathtext/
---
Obsahuje třídy pro práci s matematickým textem v prezentacích Microsoft PowerPoint.

## Třídy

| Třída | Popis |
| --- | --- |
| [BaseScript](./basescript) | Matematický skript |
| [MathAccent](./mathaccent) | Určuje akcentovou funkci, skládající se ze základny a kombinované diakritické značky. Příklad: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Umožňuje vytvořit matematický akcent |
| [MathArray](./matharray) | Určuje svislé pole rovnic nebo jakýchkoli matematických objektů |
| [MathArrayFactory](./matharrayfactory) | Umožňuje vytvořit matematické pole |
| [MathBar](./mathbar) | Určuje funkci pruhu, která se skládá ze základního argumentu a nadčáry nebo podčáry |
| [MathBarFactory](./mathbarfactory) | Umožňuje vytvořit matematický pruh |
| [MathBlock](./mathblock) | Určuje instanci matematického textu, která je obsažena v MathParagraph a začíná na vlastním řádku. Všechny matematické oblasti, včetně rovnic, výrazů, polí rovnic nebo výrazů a formulí, jsou reprezentovány matematickým blokem. |
| [MathBlockFactory](./mathblockfactory) | Umožňuje vytvořit matematický blok |
| [MathBorderBox](./mathborderbox) | Vykresluje obdélníkový nebo jiný rámec kolem IMathElement. |
| [MathBorderBoxFactory](./mathborderboxfactory) | Umožňuje vytvořit matematické ohraničovací pole |
| [MathBox](./mathbox) | Určuje logické ohraničení (balení) matematického elementu. Například objekt v rámečku může sloužit jako emulátor operátoru s bodem zarovnání nebo bez něj, jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. Například operátor "==" by měl být ohraničen, aby se zabránilo zalomení řádku. |
| [MathBoxFactory](./mathboxfactory) | Umožňuje vytvořit matematické pole |
| [MathDelimiter](./mathdelimiter) | Určuje objekt oddělovače, který se skládá z otevíracích a uzavíracích znaků (jako jsou závorky, složené závorky, hranaté závorky a svislé čáry) a jednoho nebo více matematických elementů uvnitř, oddělených určeným znakem. Příklady: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Umožňuje vytvořit matematický oddělovač |
| [MathElementBase](./mathelementbase) | Základní třída pro IMathElement s implementací některých metod společných pro všechny odvozené třídy. Pouze pro interní použití. Děděná třída musí být IMathElement. |
| [MathematicalText](./mathematicaltext) | Matematický text |
| [MathematicalTextFactory](./mathematicaltextfactory) | Umožňuje vytvořit prvek MathematicalText |
| [MathFraction](./mathfraction) | Určuje objekt zlomku, který se skládá z čitatele a jmenovatele oddělených čárou zlomku. Čára zlomku může být vodorovná nebo šikmá, v závislosti na vlastnostech zlomku. Objekt zlomku se také používá k reprezentaci funkce zásobníku, která umisťuje jeden element nad druhý bez čáry zlomku. |
| [MathFractionFactory](./mathfractionfactory) | Umožňuje vytvořit matematický zlomek |
| [MathFunction](./mathfunction) | Určuje funkci argumentu. |
| [MathFunctionFactory](./mathfunctionfactory) | Umožňuje vytvořit matematickou funkci |
| [MathGroupingCharacter](./mathgroupingcharacter) | Určuje seskupovací symbol nad nebo pod výrazem, obvykle pro zdůraznění vztahu mezi elementy. |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Umožňuje vytvořit matematický seskupovací znak |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Určuje objekt dolního a horního indexu, který se skládá ze základny a dolního a horního indexu umístěných vlevo od základny. |
| [MathLimit](./mathlimit) | Určuje objekt limitu, který se skládá z textu na základní lince a zmenšeného textu těsně nad nebo pod ním. |
| [MathLimitFactory](./mathlimitfactory) | Umožňuje vytvořit IMathLimit |
| [MathMatrix](./mathmatrix) | Určuje objekt Matice, který se skládá z podřízených elementů uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné oddělovače. Pro umístění matice do závorek byste měli použít objekt oddělovače (IMathDelimiter). Null argumenty lze použít k vytvoření mezer v maticích. |
| [MathMatrixFactory](./mathmatrixfactory) | Umožňuje vytvořit matematickou matici |
| [MathNaryOperator](./mathnaryoperator) | Určuje n-ární matematický objekt, jako jsou součet a integrál. Skládá se z operátoru, základny (nebo operand) a volitelných horních a dolních limit. Příklady n-árních operátorů jsou: Součet, Unie, Průnik, Integrál. |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Umožňuje vytvořit IMathNaryOperator |
| [MathParagraph](./mathparagraph) | Matematický odstavec, který je kontejnerem pro matematické bloky (IMathBlock) |
| [MathParagraphFactory](./mathparagraphfactory) | Umožňuje vytvořit matematický odstavec |
| [MathPhantom](./mathphantom) | Reprezentuje fiktivní matematický objekt (&lt;m:phant&gt;), který ovlivňuje rozvržení svého podřízeného elementu, aniž by jej nutně zobrazoval. Fiktivní objekt může skrýt základní výraz při zachování jeho šířky, výšky nebo hloubky pro zarovnání vzorců nebo rezervaci místa. Viditelnost a chování geometrie jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp. |
| [MathPortion](./mathportion) | Reprezentuje část s matematickým kontextem uvnitř. |
| [MathRadical](./mathradical) | Určuje radikální funkci, která se skládá ze základny a volitelného stupně. Příklad radikálního objektu je √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Umožňuje vytvořit radikál |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Určuje objekt dolního a horního indexu, který se skládá ze základny a dolního a horního indexu umístěných vpravo od základny. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Umožňuje vytvořit IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | Určuje objekt dolního indexu, který se skládá ze základny a zmenšeného dolního indexu umístěného pod a vpravo. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Umožňuje vytvořit IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | Určuje objekt horního indexu, který se skládá ze základny a zmenšeného horního indexu umístěného nad a vpravo |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Umožňuje vytvořit IMathSuperscriptElement |

## Rozhraní

| Rozhraní | Popis |
| --- | --- |
| [IMathAccent](./imathaccent) | Určuje akcentovou funkci, skládající se ze základny a kombinované diakritické značky. Příklad: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Umožňuje vytvořit matematický akcent |
| [IMathArray](./imatharray) | Určuje svislé pole rovnic nebo jakýchkoli matematických objektů |
| [IMathArrayFactory](./imatharrayfactory) | Umožňuje vytvořit matematické pole |
| [IMathBar](./imathbar) | Určuje funkci pruhu, která se skládá ze základního argumentu a nadčáry nebo podčáry |
| [IMathBarFactory](./imathbarfactory) | Umožňuje vytvořit matematický pruh |
| [IMathBlock](./imathblock) | Určuje instanci matematického textu, která je obsažena v MathParagraph a začíná na vlastním řádku. Všechny matematické oblasti, včetně rovnic, výrazů, polí rovnic nebo výrazů a formulí, jsou reprezentovány matematickým blokem. |
| [IMathBlockCollection](./imathblockcollection) | Kolekce matematických bloků (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | Umožňuje vytvořit matematický blok |
| [IMathBorderBox](./imathborderbox) | Vykresluje obdélníkový nebo jiný rámec kolem IMathElement. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Umožňuje vytvořit matematické ohraničovací pole |
| [IMathBox](./imathbox) | Určuje logické ohraničení (balení) matematického elementu. Například objekt v rámečku může sloužit jako emulátor operátoru s bodem zarovnání nebo bez něj, jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř. Například operátor "==" by měl být ohraničen, aby se zabránilo zalomení řádku. |
| [IMathBoxFactory](./imathboxfactory) | Umožňuje vytvořit matematické pole |
| [IMathDelimiter](./imathdelimiter) | Určuje objekt oddělovače, který se skládá z otevíracích a uzavíracích znaků (jako jsou závorky, složené závorky, hranaté závorky a svislé čáry) a jednoho nebo více matematických elementů uvnitř, oddělených určeným znakem. Příklady: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Umožňuje vytvořit matematický oddělovač |
| [IMathElement](./imathelement) | Základní rozhraní pro jakýkoli matematický element: zlomek, matematický text, funkce, výraz s více elementy atd. |
| [IMathElementCollection](./imathelementcollection) | Reprezentuje kolekci matematických elementů (MathElement). |
| [IMathematicalText](./imathematicaltext) | Matematický text |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Umožňuje vytvořit prvek MathematicalText |
| [IMathFraction](./imathfraction) | Určuje objekt zlomku, který se skládá z čitatele a jmenovatele oddělených čárou zlomku. Čára zlomku může být vodorovná nebo šikmá, v závislosti na vlastnostech zlomku. Objekt zlomku se také používá k reprezentaci funkce zásobníku, která umisťuje jeden element nad druhý bez čáry zlomku. |
| [IMathFractionFactory](./imathfractionfactory) | Umožňuje vytvořit matematický zlomek |
| [IMathFunction](./imathfunction) | Určuje funkci argumentu. |
| [IMathFunctionFactory](./imathfunctionfactory) | Umožňuje vytvořit matematickou funkci |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Určuje seskupovací symbol nad nebo pod výrazem, obvykle pro zdůraznění vztahu mezi elementy. |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Umožňuje vytvořit matematický seskupovací znak |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Určuje objekt dolního a horního indexu, který se skládá ze základny a dolního a horního indexu umístěných vlevo od základny. |
| [IMathLimit](./imathlimit) | Určuje objekt limitu, který se skládá z textu na základní lince a zmenšeného textu těsně nad nebo pod ním. |
| [IMathLimitFactory](./imathlimitfactory) | Umožňuje vytvořit IMathLimit |
| [IMathMatrix](./imathmatrix) | Určuje objekt Matice, který se skládá z podřízených elementů uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné oddělovače. Pro umístění matice do závorek byste měli použít objekt oddělovače (IMathDelimiter). Null argumenty lze použít k vytvoření mezer v maticích. |
| [IMathMatrixFactory](./imathmatrixfactory) | Umožňuje vytvořit matematickou matici |
| [IMathNaryOperator](./imathnaryoperator) | Určuje n-ární matematický objekt, jako jsou součet a integrál. Skládá se z operátoru, základny (nebo operand) a volitelných horních a dolních limit. Příklady n-árních operátorů jsou: Součet, Unie, Průnik, Integrál. |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Umožňuje vytvořit IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Určuje vlastnosti IMathNaryOperator |
| [IMathParagraph](./imathparagraph) | Matematický odstavec, který je kontejnerem pro matematické bloky (IMathBlock) |
| [IMathParagraphFactory](./imathparagraphfactory) | Umožňuje vytvořit matematický odstavec |
| [IMathPhantom](./imathphantom) | Reprezentuje fiktivní matematický objekt (&lt;m:phant&gt;), který ovlivňuje rozvržení svého podřízeného elementu, aniž by jej nutně zobrazoval. Fiktivní objekt může skrýt základní výraz při zachování jeho šířky, výšky nebo hloubky pro zarovnání vzorců nebo rezervaci místa. Viditelnost a chování geometrie jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp. |
| [IMathPortion](./imathportion) | Reprezentuje část s matematickým kontextem uvnitř. |
| [IMathRadical](./imathradical) | Určuje radikální funkci, která se skládá ze základny a volitelného stupně. Příklad radikálního objektu je √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Umožňuje vytvořit radikál |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Určuje objekt dolního a horního indexu, který se skládá ze základny a dolního a horního indexu umístěných vpravo od základny. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Umožňuje vytvořit IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | Určuje objekt dolního indexu, který se skládá ze základny a zmenšeného dolního indexu umístěného pod a vpravo. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Umožňuje vytvořit IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Určuje objekt horního indexu, který se skládá ze základny a zmenšeného horního indexu umístěného nad a vpravo |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Umožňuje vytvořit IMathSuperscriptElement |

## Výčtový typ

| Výčtový typ | Popis |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | Umístění a velikost oddělovačů vzhledem k obsahu operandů |
| [MathFractionTypes](./mathfractiontypes) | Typy zlomků |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Obvyklé matematické funkce s jedním argumentem |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Obvyklé matematické funkce se dvěma argumenty |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Horizontální zarovnání |
| [MathIntegralTypes](./mathintegraltypes) | Typy matematických integrálů |
| [MathJustification](./mathjustification) | Určuje zarovnání matematického odstavce (série sousedních instancí matematického textu ve stejném odstavci) |
| [MathLimitLocations](./mathlimitlocations) | Umístění limit (dolní/horní index) v n-árních operátorech. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | Typy n-árních operátorů IMathNaryOperator (kromě integrálů) Pro integrály [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | Typ svislé mezery mezi sloupci v matici nebo poli |
| [MathSpacingRules](./mathspacingrules) | Typy mezery (vodorovné mezery) mezi sloupci matice |
| [MathTopBotPositions](./mathtopbotpositions) | Výčet pozic nahoře/dole |
| [MathVerticalAlignment](./mathverticalalignment) | Vertikální zarovnání -->

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->