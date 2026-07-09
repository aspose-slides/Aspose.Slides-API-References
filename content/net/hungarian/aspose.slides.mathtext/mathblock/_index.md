---
title: MathBlock
second_title: Aspose.Sildes for .NET API-referencia
description: Megad egy matematikai szövegpéldányt, amely egy MathParagraph-on belül található, és saját sorban kezdődik. Minden matematikai zóna, beleértve az egyenleteket, kifejezéseket, egyenletek vagy kifejezések tömbjeit és képleteket, matematikai blokk formájában van ábrázolva.
type: docs
weight: 8590
url: /hu/aspose.slides.mathtext/mathblock/
---
## MathBlock osztály

Megad egy matematikai szövegpéldányt, amely egy MathParagraph-on belül helyezkedik el, és saját sorban kezdődik. Minden matematikai zóna, beleértve az egyenleteket, kifejezéseket, egyenlet- vagy kifejezéstömböket és képleteket, matematikai blokkokként van ábrázolva.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Új MathBlock példányt inicializál. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Új matematikai blokkot hoz létre, és a megadott elemeket helyezi bele. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Új matematikai blokkot hoz létre, és a megadott elemet helyezi bele. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Megkapja a gyűjteményben ténylegesen lévő gyermek matematikai elemek számát. Csak olvasható Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Visszaad false értéket, mert a gyermekelemek gyűjteménye módosítható. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Lekéri vagy beállítja az IMathElement elemet a megadott indexen. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentus jelet (a karaktert az elem tetején). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | A gyűjtemény végéhez ad egy matematikai elemet. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | A megadott függvényt úgy veszi, hogy ez a példány a paraméter. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | A megadott függvényt úgy veszi, hogy ez a példány a paraméter. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | A megadott függvényt úgy veszi, hogy ez a példány a paraméter. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | A megadott függvényt úgy veszi, hogy ez a példány a paraméter és egy további argumentum. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | A megadott függvényt úgy veszi, hogy ez a példány a paraméter és egy további argumentum. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Eltávolítja a gyűjtemény összes elemét. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Másolja a megadott tömbbe. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Elválasztja a gyermekelemeket a megadott elválasztó karakterrel (zárójelek nélkül). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé tesz egy matematikai elemet. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | A blokk gyermekelemeit a megadott karakterek közé zárja, mint például zárójelek vagy más keretező karakterek. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | A blokk gyermekelemeit a megadott karakterek közé zárja, mint például zárójelek vagy más keretező karakterek, és elválasztja egy elválasztó karakterrel. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Egy argumentummal rendelkező függvényt vesz, ahol ez a példány a függvény neve. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Egy argumentummal rendelkező függvényt vesz, ahol ez a példány a függvény neve. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Gyermekelemeket kér le. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi, alul lévő kapcsos zárójelet használva. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi, egy csoportosító karaktert használva, például alul lévő kapcsos zárójelet vagy más. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Megállapítja egy adott matematikai elem indexét a gyűjteményben. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Beszúr egy MathElement elemet a gyűjteménybe a megadott indexnél. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | A határok nélkül veszi az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Egy matematikai elemet összekapcsol ezzel a matematikai blokkal. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Egy matematikai szöveget összekapcsol ezzel a matematikai blokkal. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Egy másik matematikai blokkot összekapcsol ezzel. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Vonalat helyez az elem tetejére. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Eltávolítja a gyűjteményből egy adott objektum első előfordulását. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Eltávolítja a gyűjteményben a megadott indexnél lévő elemet. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alul határértéket vesz. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alul határértéket vesz. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határértéket vesz. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határértéket vesz. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet keretdobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet keretdobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy dobozban lévő objektum például szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy csoportosítható úgy, hogy ne engedjen sortöréseket a belsejében. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | A gyermekelemeket függőleges sorba helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Vonalat helyez az elem aljára. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Elmenti ennek [`MathBlock`](../mathblock) tartalmát MathML formátumban. |

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