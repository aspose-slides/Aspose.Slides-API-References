---
title: MathBlock
second_title: Aspose.Sildes .NET API Referenciája
description: Megadja a MathParagraph-ban lévő matematikai szövegrész példányát, amely saját sorban kezdődik. Minden matematikai terület, beleértve az egyenleteket, kifejezéseket, egyenlet vagy kifejezés tömböket és képleteket, a math block által van reprezentálva.
type: docs
weight: 8610
url: /hu/aspose.slides.mathtext/mathblock/
---
## MathBlock osztály

Megad egy matematikai szöveg példányt, amely egy MathParagraph-ban van, és saját sorban kezdődik. Minden matematikai terület, beleértve az egyenleteket, kifejezéseket, egyenlet- vagy kifejezéstömböket és képleteket, a math block által van reprezentálva.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Új példányt hoz létre a MathBlock osztályból. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Új matematikai blokkot hoz létre, és a megadott elemeket ebbe helyezi |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Új matematikai blokkot hoz létre, és a megadott elemet ebbe helyezi |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Lekéri a gyűjteményben ténylegesen lévő gyermek matematikai elemek számát. Csak olvasható Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | False értéket ad vissza, mert a gyermekelemek gyűjteménye módosítható. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Lekéri vagy beállítja az IMathElement elemet a megadott indexnél. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Akcentusjelet állít be (a karaktert az elem tetején). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Matematikai elemet ad a gyűjtemény végehez. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt veszi, az aktuális példányt argumentumként használva. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt veszi, az aktuális példányt argumentumként használva. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt veszi, az aktuális példányt argumentumként használva. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt veszi, az aktuális példányt argumentumként, valamint a megadott további argumentumot. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt veszi, az aktuális példányt argumentumként, valamint a megadott további argumentumot. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Eltávolítja az összes elemet a gyűjteményből. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Másolja a megadott tömbbe. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Elválasztja a gyermekelemeket a megadott elválasztó karakterrel (zárójelek nélkül). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy adott típusú törtet a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy adott típusú törtet a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé helyezi a matematikai elemet. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | A blokk gyermekelemeit a megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretezi. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | A blokk gyermekelemeit a megadott karakterekkel keretezi, és egy elválasztó karakterrel választja el. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Egy argumentumfüggvényt vesz, az aktuális példányt függménynévként használva. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Egy argumentumfüggvényt vesz, az aktuális példányt függménynévként használva. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Gyermekelemek lekérése. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi, alul egy plett zárójel használatával. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi, egy csoportosító karakterrel, például alul plett zárójel vagy más karakter. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Megállapítja egy adott matematikai elem indexét a gyűjteményben. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Beszúr egy MathElement elemet a gyűjteménybe a megadott indexnél. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Az integrált veszi limit nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Összekapcsol egy matematikai elemet ezzel a matematikai blokkal. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Összekapcsol egy matematikai szöveget ezzel a matematikai blokkal. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Összekapcsol egy másik matematikai blokkot ezzel. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Feltét egy vonalat az elem tetejére. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Eltávolítja egy adott objektum első előfordulását a gyűjteményből. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Az alsó határt veszi. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Az alsó határt veszi. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Balra létrehoz alsó és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Balra létrehoz alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobbra létrehoz alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobbra létrehoz alsó és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | A felső határt veszi. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | A felső határt veszi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretes dobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretes dobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozba helyezett objektum például szolgálhat operátor emulátorként egy összeigazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedélyezzen sortöréseket benne. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | A gyermekelemeket függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Feltét egy vonalat az elem aljára. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Elmenti ennek a [`MathBlock`](../mathblock) tartalmát MathML-ként. |

### Példák

Példa:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathBlock](../imathblock)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->