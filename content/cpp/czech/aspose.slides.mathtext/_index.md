---
title: "Aspose::Slides::MathText"
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 157
url: /cs/aspose.slides.mathtext/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [BaseScript](./basescript/) | Matematický skript |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) s [Control](../aspose.slides/control/) Vlastnostmi znaků |
| [IMathAccent](./imathaccent/) | Určuje funkci akcentu, která se skládá ze základu a kombinujícího diakritického znaku Příklad: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Umožňuje vytvořit matematický akcent |
| [IMathArray](./imatharray/) | Určuje svislé pole rovnic nebo libovolných matematických objektů |
| [IMathArrayFactory](./imatharrayfactory/) | Umožňuje vytvořit matematické pole |
| [IMathBar](./imathbar/) | Určuje funkci čáry, která se skládá ze základního argumentu a horní nebo dolní čáry |
| [IMathBarFactory](./imathbarfactory/) | Umožňuje vytvořit matematickou čáru |
| [IMathBlock](./imathblock/) | Určuje instanci matematického textu, která je obsažena v [MathParagraph](./mathparagraph/) a začíná na samostatném řádku. Všechny matematické zóny, včetně rovnic, výrazů, polí rovnic nebo výrazů a vzorců, jsou reprezentovány matematickým blokem. |
| [IMathBlockCollection](./imathblockcollection/) | Sbírka matematických bloků ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Umožňuje vytvořit matematický blok |
| [IMathBorderBox](./imathborderbox/) | Vykresluje obdélníkový nebo jiný okraj kolem [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Umožňuje vytvořit matematické okrajové pole |
| [IMathBox](./imathbox/) | Určuje logické zabalení (balení) matematického prvku. Například zabalený objekt může sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. Například operátor "==" by měl být zabalen, aby se zabránilo zalomení řádků. |
| [IMathBoxFactory](./imathboxfactory/) | Umožňuje vytvořit matematické pole |
| [IMathDelimiter](./imathdelimiter/) | Určuje objekt ohraničovače, který se skládá z otevíracích a uzavíracích znaků (např. závorky, složené závorky, hranaté závorky a svislé čáry) a jednoho nebo více matematických prvků uvnitř, oddělených specifikovaným znakem. Příklady: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Umožňuje vytvořit matematický ohraničovač |
| [IMathElement](./imathelement/) | Základní rozhraní jakéhokoli matematického prvku: zlomek, matematický text, funkce, výraz s více prvky atd. |
| [IMathElementCollection](./imathelementcollection/) | Reprezentuje sbírku matematických prvků (MathElement). |
| [IMathematicalText](./imathematicaltext/) | Matematický text |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Umožňuje vytvořit prvek [MathematicalText](./mathematicaltext/) |
| [IMathFraction](./imathfraction/) | Určuje objekt zlomku, který se skládá z čitatele a jmenovatele oddělených zlomkovou čarou. Zlomková čára může být horizontální nebo úhlová, v závislosti na vlastnostech zlomku. Objekt zlomku se také používá k reprezentaci funkce stack, která umisťuje jeden prvek nad druhý bez zlomkové čáry. |
| [IMathFractionFactory](./imathfractionfactory/) | Umožňuje vytvořit matematický zlomek |
| [IMathFunction](./imathfunction/) | Určuje funkci argumentu. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Umožňuje vytvořit matematickou funkci |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Určuje seskupovací symbol nad nebo pod výrazem, obvykle pro zvýraznění vztahu mezi prvky |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Umožňuje vytvořit matematický seskupovací znak |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Určuje objekt pod- a nadřazeného indexu, který se skládá ze základu a dolního a horního indexu umístěných vlevo od základu. |
| [IMathLimit](./imathlimit/) | Určuje objekt limitu, který se skládá z textu na základní linii a zmenšeného textu ihned nad nebo pod ním. |
| [IMathLimitFactory](./imathlimitfactory/) | Umožňuje vytvořit [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Určuje objekt matice, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné ohraničovače. Pro umístění matice do závorek byste měli použít objekt ohraničovače ([IMathDelimiter](./imathdelimiter/)). Null argumenty lze použít k vytváření mezer v maticích. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Umožňuje vytvořit matematickou matici |
| [IMathNaryOperator](./imathnaryoperator/) | Určuje n-ární matematický objekt, jako je součet a integrál. Skládá se z operátoru, základu (nebo operandu) a volitelných horních a dolních limit. Příklady n-árních operátorů jsou: Summation, Union, Intersection, Integral |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Umožňuje vytvořit [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Určuje vlastnosti [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Matematický odstavec, který je kontejnér pro matematické bloky ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Umožňuje vytvořit matematický odstavec |
| [IMathPhantom](./imathphantom/) | Reprezentuje fantomový matematický objekt (<m:phant>), který ovlivňuje rozvržení svého podřízeného prvku, aniž by jej nutně zobrazoval. Fantom může skrýt svůj základní výraz při zachování šířky, výšky nebo hloubky pro zarovnání vzorců nebo rezervaci místa. Viditelnost a geometrické chování jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp. |
| [IMathPortion](./imathportion/) | Reprezentuje část s matematickým kontextem uvnitř. |
| [IMathRadical](./imathradical/) | Určuje radikální funkci, která se skládá ze základu a volitelného stupně. Příklad radikálního objektu je \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Umožňuje vytvořit matematický radikál |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Určuje objekt pod- a nadřazeného indexu, který se skládá ze základu a dolního a horního indexu umístěných vpravo od základu. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Umožňuje vytvořit [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Určuje objekt dolního indexu, který se skládá ze základu a zmenšeného dolního indexu umístěného pod a vpravo. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Umožňuje vytvořit [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Určuje objekt horního indexu, který se skládá ze základu a zmenšeného horního indexu umístěného nad a vpravo |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Umožňuje vytvořit [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Určuje funkci akcentu, která se skládá ze základu a kombinujícího diakritického znaku Příklad: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Umožňuje vytvořit matematický akcent |
| [MathArray](./matharray/) | Určuje svislé pole rovnic nebo libovolných matematických objektů |
| [MathArrayFactory](./matharrayfactory/) | Umožňuje vytvořit matematické pole |
| [MathBar](./mathbar/) | Určuje funkci čáry, která se skládá ze základního argumentu a horní nebo dolní čáry |
| [MathBarFactory](./mathbarfactory/) | Umožňuje vytvořit matematickou čáru |
| [MathBlock](./mathblock/) | Určuje instanci matematického textu, která je obsažena v [MathParagraph](./mathparagraph/) a začíná na samostatném řádku. Všechny matematické zóny, včetně rovnic, výrazů, polí rovnic nebo výrazů a vzorců, jsou reprezentovány matematickým blokem. |
| [MathBlockFactory](./mathblockfactory/) | Umožňuje vytvořit matematický blok |
| [MathBorderBox](./mathborderbox/) | Vykresluje obdélníkový nebo jiný okraj kolem [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Umožňuje vytvořit matematické ohraničovací pole |
| [MathBox](./mathbox/) | Určuje logické zabalení (balení) matematického prvku. Například zabalený objekt může sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř. Například operátor "==" by měl být zabalen, aby se zabránilo zalomení řádků. |
| [MathBoxFactory](./mathboxfactory/) | Umožňuje vytvořit matematické pole |
| [MathDelimiter](./mathdelimiter/) | Určuje objekt ohraničovače, který se skládá z otevíracích a uzavíracích znaků (např. závorky, složené závorky, hranaté závorky a svislé čáry) a jednoho nebo více matematických prvků uvnitř, oddělených specifikovaným znakem. Příklady: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Umožňuje vytvořit matematický ohraničovač |
| [MathElementBase](./mathelementbase/) | Základní třída pro [IMathElement](./imathelement/) s implementací některých metod, které jsou společné všem zděděným třídám. Pouze pro interní použití. Děděná třída musí být [IMathElement](./imathelement/). |
| [MathematicalText](./mathematicaltext/) | Matematický text |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Umožňuje vytvořit prvek [MathematicalText](./mathematicaltext/) |
| [MathFraction](./mathfraction/) | Určuje objekt zlomku, který se skládá z čitatele a jmenovatele oddělených zlomkovou čarou. Zlomková čára může být horizontální nebo úhlová, v závislosti na vlastnostech zlomku. Objekt zlomku se také používá k reprezentaci funkce stack, která umisťuje jeden prvek nad druhý bez zlomkové čáry. |
| [MathFractionFactory](./mathfractionfactory/) | Umožňuje vytvořit matematický zlomek |
| [MathFunction](./mathfunction/) | Určuje funkci argumentu. |
| [MathFunctionFactory](./mathfunctionfactory/) | Umožňuje vytvořit matematickou funkci |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Určuje seskupovací symbol nad nebo pod výrazem, obvykle pro zvýraznění vztahu mezi prvky |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Umožňuje vytvořit matematický seskupovací znak |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Určuje objekt pod- a nadřazeného indexu, který se skládá ze základu a dolního a horního indexu umístěných vlevo od základu. |
| [MathLimit](./mathlimit/) | Určuje objekt limitu, který se skládá z textu na základní linii a zmenšeného textu ihned nad nebo pod ním. |
| [MathLimitFactory](./mathlimitfactory/) | Umožňuje vytvořit [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Určuje objekt matice, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné ohraničovače. Pro umístění matice do závorek byste měli použít objekt ohraničovače ([IMathDelimiter](./imathdelimiter/)). Null argumenty lze použít k vytváření mezer v maticích. |
| [MathMatrixFactory](./mathmatrixfactory/) | Umožňuje vytvořit matematickou matici |
| [MathNaryOperator](./mathnaryoperator/) | Určuje n-ární matematický objekt, jako je součet a integrál. Skládá se z operátoru, základu (nebo operandu) a volitelných horních a dolních limit. Příklady n-árních operátorů jsou: Summation, Union, Intersection, Integral |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Umožňuje vytvořit [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Matematický odstavec, který je kontejnér pro matematické bloky ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Umožňuje vytvořit matematický odstavec |
| [MathPhantom](./mathphantom/) | Reprezentuje fantomový matematický objekt (<m:phant>), který ovlivňuje rozvržení svého podřízeného prvku, aniž by jej nutně zobrazoval. Fantom může skrýt svůj základní výraz při zachování šířky, výšky nebo hloubky pro zarovnání vzorců nebo rezervaci místa. Viditelnost a geometrické chování jsou řízeny vlastnostmi jako Show, ZeroWid, ZeroAsc, ZeroDesc a Transp. |
| [MathPortion](./mathportion/) | Reprezentuje část s matematickým kontextem uvnitř. |
| [MathRadical](./mathradical/) | Určuje radikální funkci, která se skládá ze základu a volitelného stupně. Příklad radikálního objektu je \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Umožňuje vytvořit matematický radikál |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Určuje objekt pod- a nadřazeného indexu, který se skládá ze základu a dolního a horního indexu umístěných vpravo od základu. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Umožňuje vytvořit [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Určuje objekt dolního indexu, který se skládá ze základu a zmenšeného dolního indexu umístěného pod a vpravo. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Umožňuje vytvořit [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Určuje objekt horního indexu, který se skládá ze základu a zmenšeného horního indexu umístěného nad a vpravo |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Umožňuje vytvořit [IMathSuperscriptElement](./imathsuperscriptelement/) |

## Výčty

| Výčet | Popis |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | Umístění a velikost ohraničovačů vzhledem k obsahu operandů |
| [MathFractionTypes](./mathfractiontypes/) | Typy zlomků |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Běžné matematické funkce s jedním argumentem |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Běžné matematické funkce se dvěma argumenty |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Horizontální zarovnání |
| [MathIntegralTypes](./mathintegraltypes/) | Typy matematických integrálů |
| [MathJustification](./mathjustification/) | Určuje zarovnání matematického odstavce (série sousedních instancí matematického textu ve stejném odstavci) |
| [MathLimitLocations](./mathlimitlocations/) | Umístění limit (dolní/horní index) v n-árních operátorech. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | Typy n-árních operátorů [IMathNaryOperator](./imathnaryoperator/) (kromě integrálů) Pro integrály [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | Typ svislého odsazení mezi sloupci v matici nebo poli |
| [MathSpacingRules](./mathspacingrules/) | Typy mezery (horizontálního odsazení) mezi sloupci matice |
| [MathTopBotPositions](./mathtopbotpositions/) | Výčet pozic nahoře/dole |
| [MathVerticalAlignment](./mathverticalalignment/) | Vertikální zarovnání |