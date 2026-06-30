---
title: MathBlock
second_title: Aspose.Sildes .NET API Referenciája
description: Megad egy olyan matematikai szövegrészt, amely egy MathParagraphon belül található és saját sorban kezdődik. Minden matematikai zóna, beleértve az egyenleteket, kifejezéseket, egyenletek vagy kifejezések tömbjeit és képleteket, egy MathBlock által van ábrázolva.
type: docs
weight: 8570
url: /hu/aspose.slides.mathtext/mathblock/
---
## MathBlock osztály

Megad egy matematikai szövegrészt, amely egy MathParagraphon belül helyezkedik el, és saját sorban kezdődik. Minden matematikai zóna, beleértve egyenleteket, kifejezéseket, egyenletek vagy kifejezések tömbjeit, valamint képleteket, egy MathBlock által van ábrázolva.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Új MathBlock osztálypéldányt hoz létre. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Új matematikai blokkot hoz létre, és a megadott elemeket elhelyezi benne. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Új matematikai blokkot hoz létre, és a megadott elemet elhelyezi benne. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | A gyűjteményben ténylegesen tárolt gyermek matematikai elemek számát adja vissza. Csak olvasható Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | False értéket ad vissza, mert a gyermekelemek gyűjteménye módosítható. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Az adott indexű IMathElementet adja vissza vagy állítja be. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Akcentusjelet állít be (karakter a elem tetején). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Egy matematikai elemet ad a gyűjtemény végéhez. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Függvényt hív meg, amely argumentumként ezt az példányt veszi. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Függvényt hív meg, amely argumentumként ezt az példányt veszi. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Függvényt hív meg, amely argumentumként ezt az példányt veszi. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Függvényt hív meg, amely argumentumként ezt az példányt és egy megadott további argumentumot veszi. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Függvényt hív meg, amely argumentumként ezt az példányt és egy megadott további argumentumot veszi. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Eltávolítja a gyűjtemény összes elemét. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | A megadott tömbbe másolja. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Elválasztja a gyermekelemeket a megadott elválasztó karakterrel (a szögletes zárójelek nélkül). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy meghatározott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy meghatározott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé helyezi a matematikai elemet. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | A blokkok gyermekelemeit a megadott karakterekkel, például zárójelekbe vagy más karakterekbe keretezi. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | A blokkok gyermekelemeit a megadott karakterekkel (például zárójelek) keretezi és egy elválasztó karakterrel határolja. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Egy argumentumfüggvényt vesz fel, amelynek neve ez az példány. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Egy argumentumfüggvényt vesz fel, amelynek neve ez az példány. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Gyermekelemeket ad vissza. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi, alsó kapcsos zárójel használatával. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójellel vagy más karakterrel. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Meghatározza egy adott matematikai elem indexét a gyűjteményben. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | A megadott indexnél egy MathElementet beszúr a gyűjteménybe. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Az integrált veszi határok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Az integrált veszi. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Az integrált veszi. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Összekapcsol egy matematikai elemet ezzel a matematikai blokkal. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Összekapcsol egy matematikai szöveget ezzel a matematikai blokkal. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Egy másik matematikai blokkot kapcsol össze ezzel. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary operátort hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary operátort hoz létre. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | A elem tetejére egy vonalat helyez. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott argumentum adott fokú matematikai gyökét. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott argumentum adott fokú matematikai gyökét. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz fel. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz fel. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alhájat hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alhájat hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon al- és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon al- és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon al- és felső indexet hoz létre. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon al- és felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz fel. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz fel. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretbe helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretbe helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amely egyenlet vagy más matematikai szöveg komponenseinek csoportosítására szolgál. Egy dobozba helyezett objektum például operátor emulátorként működhet igaz vagy hamis igazítási ponttal, sortörés pontként szolgálhat, vagy úgy csoportosítható, hogy ne engedjen sortörést benne. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | A gyermekelemeket függőleges sorozatba helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Az elem aljára egy vonalat helyez. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Mentse ennek a [`MathBlock`](../mathblock) tartalmát MathML-ként. |

### Példák

Example:

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