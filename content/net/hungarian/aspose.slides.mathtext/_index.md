---
title: Aspose.Slides.MathText
second_title: Aspose.Sildes a .NET API referencia
description: Olyan osztályokat tartalmaz, amelyek a Microsoft PowerPoint prezentációkban a matematikai szöveggel való munkához használhatók.
type: docs
weight: 140
url: /hu/aspose.slides.mathtext/
---
Tartalmaz osztályokat a matematikai szöveg Microsoft PowerPoint prezentációkban való kezeléséhez.

## Osztályok

| Osztály | Leírás |
| --- | --- |
| [BaseScript](./basescript) | Matematikai szkript |
| [MathAccent](./mathaccent) | Megadja a hangsúly funkciót, amely egy alap és egy kombináló diakritikus jelből áll. Példa: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Lehetővé teszi egy matematikai hangsúly létrehozását |
| [MathArray](./matharray) | Megadja az egyenletek vagy bármely matematikai objektumok függőleges elrendezését |
| [MathArrayFactory](./matharrayfactory) | Lehetővé teszi egy matematikai tömb létrehozását |
| [MathBar](./mathbar) | Megadja a sáv funkciót, amely egy alap argumentumból és egy felső vagy alsó vonalból áll |
| [MathBarFactory](./mathbarfactory) | Lehetővé teszi egy matematikai sáv létrehozását |
| [MathBlock](./mathblock) | Megad egy matematikai szövegrész példányt, amely egy MathParagraph-ban található és saját sorban kezdődik. Az összes matematikai zóna, beleértve az egyenleteket, kifejezéseket, egyenleteket vagy kifejezéseket tartalmazó tömböket és képleteket, egy matematikai blokkban van ábrázolva. |
| [MathBlockFactory](./mathblockfactory) | Lehetővé teszi egy matematikai blokk létrehozását |
| [MathBorderBox](./mathborderbox) | Téglalap alakú vagy más keretet rajzol az IMathElement köré |
| [MathBorderBoxFactory](./mathborderboxfactory) | Lehetővé teszi egy matematikai keretdoboz létrehozását |
| [MathBox](./mathbox) | Megadja a matematikai elem logikai keretezését (csomagolását). Például egy keretezett objektum szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, sorvége jelzőként, vagy csoportosítható úgy, hogy ne engedje a sorok törését. Például a "==" operátort keretezni kell, hogy megakadályozzuk a sorok törését. |
| [MathBoxFactory](./mathboxfactory) | Lehetővé teszi egy matematikai doboz létrehozását |
| [MathDelimiter](./mathdelimiter) | Megadja a határoló objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz belül, amelyeket egy megadott karakterrel választ el. Példák: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Lehetővé teszi egy matematikai határoló létrehozását |
| [MathElementBase](./mathelementbase) | Alaposztály az IMathElement számára, amely tartalmazza néhány, az összes örökölt osztályban közös metódust. Csak belső használatra. Az örökölt osztálynak IMathElementnek kell lennie. |
| [MathematicalText](./mathematicaltext) | Matematikai szöveg |
| [MathematicalTextFactory](./mathematicaltextfactory) | Lehetővé teszi egy MathematicalText elem létrehozását |
| [MathFraction](./mathfraction) | Megadja a tört objektumot, amely számlálóból és nevezőből áll, egy törtvonal választja el őket. A törtvonal lehet vízszintes vagy átlós, a tört tulajdonságaitól függően. A tört objektum használható a stack (verem) funkció ábrázolására is, amely egy elemet helyez egy másik fölé, törtvonal nélkül. |
| [MathFractionFactory](./mathfractionfactory) | Lehetővé teszi egy matematikai tört létrehozását |
| [MathFunction](./mathfunction) | Megad egy argumentumfüggvényt. |
| [MathFunctionFactory](./mathfunctionfactory) | Lehetővé teszi egy matematikai függvény létrehozását |
| [MathGroupingCharacter](./mathgroupingcharacter) | Megadja a kifejezés fölött vagy alatt elhelyezkedő csoportosító szimbólumot, amely általában kiemeli az elemek közötti kapcsolatot. |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Lehetővé teszi egy matematikai csoportosító karakter létrehozását |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Megadja a Sub-Superscript objektumot, amely egy alap, egy alsóindex és egy felsőindexből áll, és az alap bal oldalán helyezkedik el. |
| [MathLimit](./mathlimit) | Megadja a Limit objektumot, amely a vonal alatti szöveget és egy azonnal fölötte vagy alatt lévő kisebb méretű szöveget tartalmaz. |
| [MathLimitFactory](./mathlimitfactory) | Lehetővé teszi egy IMathLimit létrehozását |
| [MathMatrix](./mathmatrix) | Megadja a Matrix objektumot, amely gyermekelemekből áll, sorokban és oszlopokban elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített határolókkal. A mátrix zárójelekbe helyezéséhez határoló objektumot (IMathDelimiter) kell használni. Null értékekkel részeket lehet létrehozni a mátrixokban. |
| [MathMatrixFactory](./mathmatrixfactory) | Lehetővé teszi egy matematikai mátrix létrehozását |
| [MathNaryOperator](./mathnaryoperator) | Megad egy N-áris matematikai objektumot, például összegzést vagy integrált. Tartalmaz egy operátort, egy alapot (vagy operandust), valamint opcionális felső és alsó határokat. N-áris operátorok példái: összegzés, unió, metszet, integrál. |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Lehetővé teszi egy IMathNaryOperator létrehozását |
| [MathParagraph](./mathparagraph) | Matematikai bekezdés, amely a matematikai blokkok (IMathBlock) tárolója. |
| [MathParagraphFactory](./mathparagraphfactory) | Lehetővé teszi egy matematikai bekezdés létrehozását |
| [MathPhantom](./mathphantom) | Egy fantom matematikai objektum (<m:phant>) képviseli, amely befolyásolja a gyermekeleme elrendezését anélkül, hogy feltétlenül megjelenne. A fantom elrejtheti az alapkifejezést, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy hely lefoglalásához. A láthatóságot és a geometriai viselkedést olyan tulajdonságok vezérlik, mint Show, ZeroWid, ZeroAsc, ZeroDesc és Transp. |
| [MathPortion](./mathportion) | Egy belső matematikai kontextussal rendelkező részt jelöl. |
| [MathRadical](./mathradical) | Megadja a radikális függvényt, amely egy alapból és egy opcionális fokból áll. A radikális objektus példája: √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Lehetővé teszi egy matematikai radikál létrehozását |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Megadja a Sub-Superscript objektumot, amely egy alapból, egy alsóindexből és egy felsőindexből áll, és az alap jobb oldalán helyezkedik el. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Lehetővé teszi egy IMathRightSubSuperscriptElementFactory létrehozását |
| [MathSubscriptElement](./mathsubscriptelement) | Megadja a subscript objektumot, amely egy alapból és egy kisebb méretű alsóindexből áll, amely a jobb oldal alatta helyezkedik el. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Lehetővé teszi egy IMathSubscriptElement létrehozását |
| [MathSuperscriptElement](./mathsuperscriptelement) | Megadja a superscript objektumot, amely egy alapból és egy kisebb méretű felsőindexből áll, amely a jobb oldal fölött helyezkedik el. |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Lehetővé teszi egy IMathSuperscriptElement létrehozását |

## Interfészek

| Interfész | Leírás |
| --- | --- |
| [IMathAccent](./imathaccent) | Megadja a hangsúly funkciót, amely egy alap és egy kombináló diakritikus jelből áll. Példa: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Lehetővé teszi egy matematikai hangsúly létrehozását |
| [IMathArray](./imatharray) | Megadja az egyenletek vagy bármely matematikai objektumok függőleges elrendezését |
| [IMathArrayFactory](./imatharrayfactory) | Lehetővé teszi egy matematikai tömb létrehozását |
| [IMathBar](./imathbar) | Megadja a sáv funkciót, amely egy alap argumentumból és egy felső vagy alsó vonalból áll |
| [IMathBarFactory](./imathbarfactory) | Lehetővé teszi egy matematikai sáv létrehozását |
| [IMathBlock](./imathblock) | Megad egy matematikai szövegrész példányt, amely egy MathParagraph-ban található és saját sorban kezdődik. Az összes matematikai zóna, beleértve az egyenleteket, kifejezéseket, egyenleteket vagy kifejezéseket tartalmazó tömböket és képleteket, egy matematikai blokkban van ábrázolva. |
| [IMathBlockCollection](./imathblockcollection) | Matematikai blokkok (IMathBlock) gyűjteménye |
| [IMathBlockFactory](./imathblockfactory) | Lehetővé teszi egy matematikai blokk létrehozását |
| [IMathBorderBox](./imathborderbox) | Téglalap alakú vagy más keretet rajzol az IMathElement köré |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Lehetővé teszi egy matematikai keretdoboz létrehozását |
| [IMathBox](./imathbox) | Megadja a matematikai elem logikai keretezését (csomagolását). Például egy keretezett objektum szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, sorvége jelzőként, vagy csoportosítható úgy, hogy ne engedje a sorok törését. Például a "==" operátort keretezni kell, hogy megakadályozzuk a sorok törését. |
| [IMathBoxFactory](./imathboxfactory) | Lehetővé teszi egy matematikai doboz létrehozását |
| [IMathDelimiter](./imathdelimiter) | Megadja a határoló objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz belül, amelyeket egy megadott karakterrel választ el. Példák: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Lehetővé teszi egy matematikai határoló létrehozását |
| [IMathElement](./imathelement) | Bármely matematikai elem (tört, matematikai szöveg, függvény, több elemből álló kifejezés stb.) alapinterfésze |
| [IMathElementCollection](./imathelementcollection) | Matematikai elemek (MathElement) gyűjteményét képviseli |
| [IMathematicalText](./imathematicaltext) | Matematikai szöveg |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Lehetővé teszi egy MathematicalText elem létrehozását |
| [IMathFraction](./imathfraction) | Megadja a tört objektumot, amely számlálóból és nevezőből áll, egy törtvonal választja el őket. A törtvonal lehet vízszintes vagy átlós, a tört tulajdonságaitól függően. A tört objektum használható a stack (verem) funkció ábrázolására is, amely egy elemet helyez egy másik fölé, törtvonal nélkül. |
| [IMathFractionFactory](./imathfractionfactory) | Lehetővé teszi egy matematikai tört létrehozását |
| [IMathFunction](./imathfunction) | Megad egy argumentumfüggvényt. |
| [IMathFunctionFactory](./imathfunctionfactory) | Lehetővé teszi egy matematikai függvény létrehozását |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Megadja a kifejezés fölött vagy alatt elhelyezkedő csoportosító szimbólumot, amely általában kiemeli az elemek közötti kapcsolatot. |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Lehetővé teszi egy matematikai csoportosító karakter létrehozását |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Megadja a Sub-Superscript objektumot, amely egy alap, egy alsóindex és egy felsőindexből áll, és az alap bal oldalán helyezkedik el. |
| [IMathLimit](./imathlimit) | Megadja a Limit objektumot, amely a vonal alatti szöveget és egy azonnal fölötte vagy alatt lévő kisebb méretű szöveget tartalmaz. |
| [IMathLimitFactory](./imathlimitfactory) | Lehetővé teszi egy IMathLimit létrehozását |
| [IMathMatrix](./imathmatrix) | Megadja a Matrix objektumot, amely gyermekelemekből áll, sorokban és oszlopokban elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített határolókkal. A mátrix zárójelekbe helyezéséhez határoló objektumot (IMathDelimiter) kell használni. Null értékekkel részeket lehet létrehozni a mátrixokban. |
| [IMathMatrixFactory](./imathmatrixfactory) | Lehetővé teszi egy matematikai mátrix létrehozását |
| [IMathNaryOperator](./imathnaryoperator) | Megad egy N-áris matematikai objektumot, például összegzést vagy integrált. Tartalmaz egy operátort, egy alapot (vagy operandust), valamint opcionális felső és alsó határokat. N-áris operátorok példái: összegzés, unió, metszet, integrál. |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Lehetővé teszi egy IMathNaryOperator létrehozását |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Megadja az IMathNaryOperator tulajdonságait |
| [IMathParagraph](./imathparagraph) | Matematikai bekezdés, amely a matematikai blokkok (IMathBlock) tárolója. |
| [IMathParagraphFactory](./imathparagraphfactory) | Lehetővé teszi egy matematikai bekezdés létrehozását |
| [IMathPhantom](./imathphantom) | Egy fantom matematikai objektum (<m:phant>) képviseli, amely befolyásolja a gyermekeleme elrendezését anélkül, hogy feltétlenül megjelenne. A fantom elrejtheti az alapkifejezést, miközben megőrzi a szélességét, magasságát vagy mélységét a képletek igazításához vagy hely lefoglalásához. A láthatóságot és a geometriai viselkedést olyan tulajdonságok vezérlik, mint Show, ZeroWid, ZeroAsc, ZeroDesc és Transp. |
| [IMathPortion](./imathportion) | Egy belső matematikai kontextussal rendelkező részt jelöl. |
| [IMathRadical](./imathradical) | Megadja a radikális függvényt, amely egy alapból és egy opcionális fokból áll. A radikális objektus példája: √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Lehetővé teszi egy matematikai radikál létrehozását |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Megadja a Sub-Superscript objektumot, amely egy alapból, egy alsóindexből és egy felsőindexből áll, és az alap jobb oldalán helyezkedik el. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Lehetővé teszi egy IMathRightSubSuperscriptElementFactory létrehozását |
| [IMathSubscriptElement](./imathsubscriptelement) | Megadja a subscript objektumot, amely egy alapból és egy kisebb méretű alsóindexből áll, amely a jobb oldal alatta helyezkedik el. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Lehetővé teszi egy IMathSubscriptElement létrehozását |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Megadja a superscript objektumot, amely egy alapból és egy kisebb méretű felsőindexből áll, amely a jobb oldal fölött helyezkedik el. |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Lehetővé teszi egy IMathSuperscriptElement létrehozását |

## Felsorolás

| Felsorolás | Leírás |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | A határolók helyzete és mérete a operandusok tartalmához képest |
| [MathFractionTypes](./mathfractiontypes) | Tört típusok |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Általános matematikai függvények egy argumentummal |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Általános matematikai függvények két argumentummal |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Vízszintes igazítás |
| [MathIntegralTypes](./mathintegraltypes) | Matematikai integrál típusok |
| [MathJustification](./mathjustification) | Megadja a matematikai bekezdés igazítását (az azonos bekezdésen belül egymás mellett lévő matematikai szöveg példányok sorozata) |
| [MathLimitLocations](./mathlimitlocations) | A határok (alsóindex/felsőindex) helye n-áris operátorokban. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | N-áris operátor IMathNaryOperator típusok (integrálok kivételével) Integrálokhoz [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | Az oszlopok közötti függőleges távolság típusa egy mátrixban vagy tömbben |
| [MathSpacingRules](./mathspacingrules) | Az oszlopok közötti hézag (vízszintes távolság) típusai egy mátrixban |
| [MathTopBotPositions](./mathtopbotpositions) | Felső/alsó pozíciók felsorolása |
| [MathVerticalAlignment](./mathverticalalignment) | Függőleges igazítás |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->