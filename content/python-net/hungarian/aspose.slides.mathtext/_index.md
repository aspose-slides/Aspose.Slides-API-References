---
title: aspose.slides.mathtext
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/
---
Matematikai szöveg kezeléséhez Microsoft PowerPoint-prezentációkban tartalmaz osztályokat.
## Osztályok

| Osztály | Leírás |
| :- | :- |
| [`BaseScript`](/slides/python-net/hu/aspose.slides.mathtext/basescript/) | Math script |
| [`IMathAccent`](/slides/python-net/hu/aspose.slides.mathtext/imathaccent/) | Megadja a hangsúly funkciót, amely egy alapból és egy kombináló diakritikus jelből áll<br/>            Példa: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathaccentfactory/) | Lehetővé teszi egy math accent létrehozását |
| [`IMathArray`](/slides/python-net/hu/aspose.slides.mathtext/imatharray/) | Megadja egy függőleges egyenletek vagy bármely matematikai objektumok tömbjét |
| [`IMathArrayFactory`](/slides/python-net/hu/aspose.slides.mathtext/imatharrayfactory/) | Lehetővé teszi egy math array létrehozását |
| [`IMathBar`](/slides/python-net/hu/aspose.slides.mathtext/imathbar/) | Megadja a bar funkciót, amely egy alap argumentumból és egy felső vagy alsó vonalból áll |
| [`IMathBarFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathbarfactory/) | Lehetővé teszi egy math bar létrehozását |
| [`IMathBlock`](/slides/python-net/hu/aspose.slides.mathtext/imathblock/) | Megadja a matematikai szöveg egy példányát, amely egy MathParagraph belsejében van és saját sorban kezdődik.<br/>            Minden math zone, beleértve az egyenleteket, kifejezéseket, egyenletek vagy kifejezések tömbjeit, valamint a képleteket, a math block által van reprezentálva. |
| [`IMathBlockCollection`](/slides/python-net/hu/aspose.slides.mathtext/imathblockcollection/) | A math blockok (IMathBlock) gyűjteménye |
| [`IMathBlockFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathblockfactory/) | Lehetővé teszi egy math block létrehozását |
| [`IMathBorderBox`](/slides/python-net/hu/aspose.slides.mathtext/imathborderbox/) | Téglalap vagy egyéb keretet rajzol az IMathElement köré. |
| [`IMathBorderBoxFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathborderboxfactory/) | Lehetővé teszi egy math border box létrehozását |
| [`IMathBox`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/) | Megadja a matematikai elem logikai dobozolását (csomagolását).<br/>            Például egy dobozolt objektum funkcionálhat operátor emulátorként egy igazítási ponttal vagy anélkül,<br/>            szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedje meg a sortöréseket belül.<br/>            Például a "==" operátort dobozolni kell a sortörések megelőzése érdekében. |
| [`IMathBoxFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathboxfactory/) | Lehetővé teszi egy math box létrehozását |
| [`IMathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/imathdelimiter/) | Megadja a delimiter objektumot, amely nyitó és záró karakterekből (például zárójelek,<br/>            kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz belül, egy meghatározott karakterrel elválasztva.<br/>            Példák: (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathdelimiterfactory/) | Lehetővé teszi egy math delimiter létrehozását |
| [`IMathElement`](/slides/python-net/hu/aspose.slides.mathtext/imathelement/) | Bármely matematikai elem alappontja: <br/>            fraction, mathmatical text, function, expression with multiple elements etc |
| [`IMathElementCollection`](/slides/python-net/hu/aspose.slides.mathtext/imathelementcollection/) | Matematikai elemek (MathElement) gyűjteményét reprezentálja. |
| [`IMathFraction`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/) | Megadja a fraction objektumot, amely egy számlálóból és nevezőből áll, amelyet egy fraction bar választ el.<br/>            A fraction bar lehet vízszintes vagy átlós, a fraction tulajdonságaitól függően.<br/>            A fraction objektumot a stack funkció reprezentálására is használják, amely egy elemet egy másik fölé helyez fraction bar nélkül. |
| [`IMathFractionFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathfractionfactory/) | Lehetővé teszi egy math fraction létrehozását |
| [`IMathFunction`](/slides/python-net/hu/aspose.slides.mathtext/imathfunction/) | Megadja egy argumentum függvényét. |
| [`IMathFunctionFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathfunctionfactory/) | Lehetővé teszi egy math function létrehozását |
| [`IMathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacter/) | Megadja egy csoportosító szimbólumot egy kifejezés felett vagy alatt, általában az elemek közötti kapcsolat kiemelésére |
| [`IMathGroupingCharacterFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathgroupingcharacterfactory/) | Lehetővé teszi egy math grouping karakter létrehozását |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | Megadja a Sub-Superscript objektumot, amely egy alapból és egy balra elhelyezkedő alsó- és felső indexből áll. |
| [`IMathLimit`](/slides/python-net/hu/aspose.slides.mathtext/imathlimit/) | Megadja a Limit objektumot, amely egy alapvonalra írt szöveget és azonnal fölötte vagy alatta kisebb méretű szöveget tartalmaz. |
| [`IMathLimitFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathlimitfactory/) | Lehetővé teszi IMathLimit létrehozását |
| [`IMathMatrix`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrix/) | Megadja a Matrix objektumot, amely gyermekelemeket tartalmaz egy vagy több sorban és oszlopban.<br/>            Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített delimiterekkel.<br/>            A mátrixot a zárójelekbe helyezni a delimiter objektummal (IMathDelimiter) kell.<br/>            Null argumentumok használhatók a mátrixon belüli hézagok létrehozásához. |
| [`IMathMatrixFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathmatrixfactory/) | Lehetővé teszi egy math matrix létrehozását |
| [`IMathNaryOperator`](/slides/python-net/hu/aspose.slides.mathtext/imathnaryoperator/) | Megadja egy N-ary matematikai objektumot, például Summation vagy Integral.<br/>            Egy operátort, egy alapot (vagy operandust) és opcionális felső és alsó határokat tartalmaz.<br/>            N-ary operátorok példái: Summation, Union, Intersection, Integral |
| [`IMathNaryOperatorFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathnaryoperatorfactory/) | Lehetővé teszi IMathNaryOperator létrehozását |
| [`IMathNaryOperatorProperties`](/slides/python-net/hu/aspose.slides.mathtext/imathnaryoperatorproperties/) | Megadja az IMathNaryOperator tulajdonságait |
| [`IMathParagraph`](/slides/python-net/hu/aspose.slides.mathtext/imathparagraph/) | Matematikai bekezdés, amely a matematikai blokkok (IMathBlock) tárolóját képezi |
| [`IMathParagraphFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathparagraphfactory/) | Lehetővé teszi egy math paragraph létrehozását |
| [`IMathPhantom`](/slides/python-net/hu/aspose.slides.mathtext/imathphantom/) | Egy phantom math objektumot (<m:phant>) reprezentál, amely befolyásolja a gyermekeleme elrendezését<br/>            anélkül, hogy kötelezően megjelenítené azt. A phantom elrejtheti az alapkifejezést, miközben megtartja<br/>            annak szélességét, magasságát vagy mélységét a képletek igazításához vagy helyfoglaláshoz.<br/>            A láthatóságot és a geometriai viselkedést olyan tulajdonságok vezérlik, mint a Show, ZeroWid, ZeroAsc,<br/>            ZeroDesc és a Transp. |
| [`IMathPortion`](/slides/python-net/hu/aspose.slides.mathtext/imathportion/) | Egy matematikai kontextussal rendelkező részletet reprezentál. |
| [`IMathRadical`](/slides/python-net/hu/aspose.slides.mathtext/imathradical/) | Megadja a radical funkciót, amely egy alapelemből és egy opcionális fokból áll.<br/>            A radical objektum példája: √𝑥. |
| [`IMathRadicalFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathradicalfactory/) | Lehetővé teszi egy math radical létrehozását |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | Megadja a Sub-Superscript objektumot, amely egy alapból és egy jobb oldalon elhelyezkedő alsó- és felső indexből áll. |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | Lehetővé teszi IMathRightSubSuperscriptElementFactory létrehozását |
| [`IMathSubscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/imathsubscriptelement/) | Megadja a subscript objektumot, amely egy alapból és egy kisebb méretű alsó indexből áll, amely alul és jobbra helyezkedik el. |
| [`IMathSubscriptElementFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathsubscriptelementfactory/) | Lehetővé teszi IMathSubscriptElement létrehozását |
| [`IMathSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/imathsuperscriptelement/) | Megadja a superscript objektumot, amely egy alapból és egy kisebb méretű felső indexből áll, amely felül és jobbra helyezkedik el. |
| [`IMathSuperscriptElementFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathsuperscriptelementfactory/) | Lehetővé teszi IMathSuperscriptElement létrehozását |
| [`IMathematicalText`](/slides/python-net/hu/aspose.slides.mathtext/imathematicaltext/) | Mathematical text |
| [`IMathematicalTextFactory`](/slides/python-net/hu/aspose.slides.mathtext/imathematicaltextfactory/) | Lehetővé teszi egy MathematicalText elem létrehozását |
| [`MathAccent`](/slides/python-net/hu/aspose.slides.mathtext/mathaccent/) | Megadja a hangsúly funkciót, amely egy alapból és egy kombináló diakritikus jelből áll<br/>            Példa: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathaccentfactory/) | Lehetővé teszi egy math accent létrehozását |
| [`MathArray`](/slides/python-net/hu/aspose.slides.mathtext/matharray/) | Megadja egy függőleges egyenletek vagy bármely matematikai objektumok tömbjét |
| [`MathArrayFactory`](/slides/python-net/hu/aspose.slides.mathtext/matharrayfactory/) | Lehetővé teszi egy math array létrehozását |
| [`MathBar`](/slides/python-net/hu/aspose.slides.mathtext/mathbar/) | Megadja a bar funkciót, amely egy alap argumentumból és egy felső vagy alsó vonalból áll |
| [`MathBarFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathbarfactory/) | Lehetővé teszi egy math bar létrehozását |
| [`MathBlock`](/slides/python-net/hu/aspose.slides.mathtext/mathblock/) | Megadja a matematikai szöveg egy példányát, amely egy MathParagraph belsejében van és saját sorban kezdődik.<br/>            Minden math zone, beleértve az egyenleteket, kifejezéseket, egyenletek vagy kifejezések tömbjeit, valamint a képleteket, a math block által van reprezentálva. |
| [`MathBlockFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathblockfactory/) | Lehetővé teszi egy math block létrehozását |
| [`MathBorderBox`](/slides/python-net/hu/aspose.slides.mathtext/mathborderbox/) | Téglalap vagy egyéb keretet rajzol az IMathElement köré. |
| [`MathBorderBoxFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathborderboxfactory/) | Lehetővé teszi egy math border box létrehozását |
| [`MathBox`](/slides/python-net/hu/aspose.slides.mathtext/mathbox/) | Megadja a matematikai elem logikai dobozolását (csomagolását).<br/>            Például egy dobozolt objektum funkcionálhat operátor emulátorként egy igazítási ponttal vagy anélkül,<br/>            szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedje meg a sortöréseket belül.<br/>            Például a "==" operátort dobozolni kell a sortörések megelőzése érdekében. |
| [`MathBoxFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathboxfactory/) | Lehetővé teszi egy math box létrehozását |
| [`MathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter/) | Megadja a delimiter objektumot, amely nyitó és záró karakterekből (például zárójelek,<br/>            kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz belül, egy meghatározott karakterrel elválasztva.<br/>            Példák: (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiterfactory/) | Lehetővé teszi egy math delimiter létrehozását |
| [`MathElementBase`](/slides/python-net/hu/aspose.slides.mathtext/mathelementbase/) | IMathElement alaposztálya, amely bizonyos, az összes származtatott osztályra közös metódusok implementációját tartalmazza.<br/>            Kizárólag belső használatra. Az örökölt osztálynak IMathElement-nek kell lennie. |
| [`MathFraction`](/slides/python-net/hu/aspose.slides.mathtext/mathfraction/) | Megadja a fraction objektumot, amely egy számlálóból és nevezőből áll, amelyet egy fraction bar választ el.<br/>            A fraction bar lehet vízszintes vagy átlós, a fraction tulajdonságaitól függően.<br/>            A fraction objektumot a stack funkció reprezentálására is használják, amely egy elemet egy másik fölé helyez fraction bar nélkül. |
| [`MathFractionFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathfractionfactory/) | Lehetővé teszi egy math fraction létrehozását |
| [`MathFunction`](/slides/python-net/hu/aspose.slides.mathtext/mathfunction/) | Megadja egy argumentum függvényét. |
| [`MathFunctionFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathfunctionfactory/) | Lehetővé teszi egy math function létrehozását |
| [`MathGroupingCharacter`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacter/) | Megadja egy csoportosító szimbólumot egy kifejezés felett vagy alatt, általában az elemek közötti kapcsolat kiemelésére |
| [`MathGroupingCharacterFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathgroupingcharacterfactory/) | Lehetővé teszi egy math grouping karakter létrehozását |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | Megadja a Sub-Superscript objektumot, amely egy alapból és egy balra elhelyezkedő alsó- és felső indexből áll. |
| [`MathLimit`](/slides/python-net/hu/aspose.slides.mathtext/mathlimit/) | Megadja a Limit objektumot, amely egy alapvonalra írt szöveget és azonnal fölötte vagy alatta kisebb méretű szöveget tartalmaz. |
| [`MathLimitFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathlimitfactory/) | Lehetővé teszi IMathLimit létrehozását |
| [`MathMatrix`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrix/) | Megadja a Matrix objektumot, amely gyermekelemeket tartalmaz egy vagy több sorban és oszlopban.<br/>            Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített delimiterekkel.<br/>            A mátrixot a zárójelekbe helyezni a delimiter objektummal (IMathDelimiter) kell.<br/>            Null argumentumok használhatók a mátrixon belüli hézagok létrehozásához. |
| [`MathMatrixFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathmatrixfactory/) | Lehetővé teszi egy math matrix létrehozását |
| [`MathNaryOperator`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperator/) | Megadja egy N-ary matematikai objektumot, például Summation vagy Integral.<br/>            Egy operátort, egy alapot (vagy operandust) és opcionális felső és alsó határokat tartalmaz.<br/>            N-ary operátorok példái: Summation, Union, Intersection, Integral |
| [`MathNaryOperatorFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperatorfactory/) | Lehetővé teszi IMathNaryOperator létrehozását |
| [`MathParagraph`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraph/) | Matematikai bekezdés, amely a matematikai blokkok (IMathBlock) tárolóját képezi |
| [`MathParagraphFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathparagraphfactory/) | Lehetővé teszi egy math paragraph létrehozását |
| [`MathPhantom`](/slides/python-net/hu/aspose.slides.mathtext/mathphantom/) | Egy phantom math objektumot (<m:phant>) reprezentál, amely befolyásolja a gyermekeleme elrendezését<br/>            anélkül, hogy kötelezően megjelenítené azt. A phantom elrejtheti az alapkifejezést, miközben megtartja<br/>            annak szélességét, magasságát vagy mélységét a képletek igazításához vagy helyfoglaláshoz.<br/>            A láthatóságot és a geometriai viselkedést olyan tulajdonságok vezérlik, mint a Show, ZeroWid, ZeroAsc,<br/>            ZeroDesc és a Transp. |
| [`MathPortion`](/slides/python-net/hu/aspose.slides.mathtext/mathportion/) | Egy matematikai kontextussal rendelkező részletet reprezentál. |
| [`MathRadical`](/slides/python-net/hu/aspose.slides.mathtext/mathradical/) | Megadja a radical funkciót, amely egy alapelemből és egy opcionális fokból áll.<br/>            A radical objektum példája: √𝑥. |
| [`MathRadicalFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathradicalfactory/) | Lehetővé teszi egy math radical létrehozását |
| [`MathRightSubSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | Megadja a Sub-Superscript objektumot, amely egy alapból és egy jobb oldalon elhelyezkedő alsó- és felső indexből áll. |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | Lehetővé teszi IMathRightSubSuperscriptElementFactory létrehozását |
| [`MathSubscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/mathsubscriptelement/) | Megadja a subscript objektumot, amely egy alapból és egy kisebb méretű alsó indexből áll, amely alul és jobbra helyezkedik el. |
| [`MathSubscriptElementFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathsubscriptelementfactory/) | Lehetővé teszi IMathSubscriptElement létrehozását |
| [`MathSuperscriptElement`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelement/) | Megadja a superscript objektumot, amely egy alapból és egy kisebb méretű felső indexből áll, amely felül és jobbra helyezkedik el. |
| [`MathSuperscriptElementFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathsuperscriptelementfactory/) | Lehetővé teszi IMymSuperscriptElement létrehozását |
| [`MathematicalText`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltext/) | Mathematical text |
| [`MathematicalTextFactory`](/slides/python-net/hu/aspose.slides.mathtext/mathematicaltextfactory/) | Lehetővé teszi egy MathematicalText elem létrehozását |

## Enumerációk

| Enumeráció | Leírás |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimitershape/) | A delimiterok helyzete és mérete a operandusok tartalmához képest |
| [`MathFractionTypes`](/slides/python-net/hu/aspose.slides.mathtext/mathfractiontypes/) | Fraction Types |
| [`MathFunctionsOfOneArgument`](/slides/python-net/hu/aspose.slides.mathtext/mathfunctionsofoneargument/) | Common mathematical functions of one argument |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/hu/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | Common mathematical functions of two arguments |
| [`MathHorizontalAlignment`](/slides/python-net/hu/aspose.slides.mathtext/mathhorizontalalignment/) | Horizontal Alignment |
| [`MathIntegralTypes`](/slides/python-net/hu/aspose.slides.mathtext/mathintegraltypes/) | Mathematical integral types |
| [`MathJustification`](/slides/python-net/hu/aspose.slides.mathtext/mathjustification/) | Megadja a math paragraph igazítását (egy sorba rendezett matematikai szöveg példányait ugyanabban a bekezdésben) |
| [`MathLimitLocations`](/slides/python-net/hu/aspose.slides.mathtext/mathlimitlocations/) | A limit (subscript/superscript) helye n-ary operátorokban. |
| [`MathNaryOperatorTypes`](/slides/python-net/hu/aspose.slides.mathtext/mathnaryoperatortypes/) | N-ary operátor IMathNaryOperator típusok (integrálok kivételével)<br/>            Integrálok esetén [`MathIntegralTypes`](/slides/python-net/hu/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/hu/aspose.slides.mathtext/mathrowspacingrule/) | Függőleges távolság típusai oszlopok között egy mátrixon vagy tömbön belül |
| [`MathSpacingRules`](/slides/python-net/hu/aspose.slides.mathtext/mathspacingrules/) | Hézag típusok (vízszintes távolság) oszlopok között egy mátrixon belül |
| [`MathTopBotPositions`](/slides/python-net/hu/aspose.slides.mathtext/mathtopbotpositions/) | Top/bottom positions enumeration |
| [`MathVerticalAlignment`](/slides/python-net/hu/aspose.slides.mathtext/mathverticalalignment/) | Vertical Alignment |