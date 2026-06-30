---
title: MathLeftSubSuperscriptElement
second_title: Aspose.Sildes .NET API referenciája
description: Megadja a Sub-Superscript objektumot, amely egy alapból és az alap bal oldalára helyezett alsó- és felsőindexből áll.
type: docs
weight: 8790
url: /hu/aspose.slides.mathtext/mathleftsubsuperscriptelement/
---
## MathLeftSubSuperscriptElement osztály

Meghatározza a Sub-Superscript objektumot, amely egy alappontból, valamint az alap bal oldalára helyezett alsó- és felsőindexből áll.

```csharp
public sealed class MathLeftSubSuperscriptElement : BaseScript, IMathLeftSubSuperscriptElement
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathLeftSubSuperscriptElement](mathleftsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | Inicializál egy új példányt a MathLeftSubSuperscriptElement osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Alap argumentum |
| [Subscript](../../aspose.slides.mathtext/mathleftsubsuperscriptelement/subscript) { get; } | Alsó index |
| [Superscript](../../aspose.slides.mathtext/mathleftsubsuperscriptelement/superscript) { get; } | Felső index |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentusjelzést (egy karaktert az elem tetején). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Felveszi a megadott függvényt, amely ezt az példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Felveszi a megadott függvényt, amely ezt az példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Felveszi a megadott függvényt, amely ezt az példányt használja argumentumként. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Felveszi a megadott függvényt, amely ezt az példányt használja argumentumként, valamint a megadott további argumentumot. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Felveszi a megadott függvényt, amely ezt az példányt használja argumentumként, valamint a megadott további argumentumot. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet a jelenlegi számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet a jelenlegi számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy megadott típusú törtet a jelenlegi számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy megadott típusú törtet a jelenlegi számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zárójelek közé helyezi a matematikai elemet. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | A matematikai elemet a megadott karakterek közé helyezi, például zárójelek vagy más keretező karakterek. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Egy argumentum függvényét veszi, ahol ezt az példányt használja függvénynévként. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Egy argumentum függvényét veszi, ahol ezt az példányt használja függvénynévként. |
| [GetChildren](../../aspose.slides.mathtext/mathleftsubsuperscriptelement/getchildren)() | Lekéri a gyermekelemeket. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | A elemet egy csoportba helyezi, alul kapcsos zárójel használatával. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | A elemet egy csoportba helyezi, egy csoportosító karakter, például alul kapcsos zárójel vagy más karakter használatával. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Kiválasztja az integrált korlátok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Kiválasztja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Kiválasztja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Kiválasztja az integrált. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Kiválasztja az integrált. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és matematikai blokkot hoz létre. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és matematikai blokkot hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-értelmű operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-értelmű operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | A elem tetejére vonalat helyez. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Veszi az alsó határt. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Veszi az alsó határt. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehoz alsó indexet. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehoz alsó indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Létrehoz bal oldali alsó- és felsőindexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Létrehoz bal oldali alsó- és felsőindexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Létrehoz jobb oldali alsó- és felsőindexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Létrehoz jobb oldali alsó- és felsőindexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehoz felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehoz felső indexet. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Veszi a felső határt. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Veszi a felső határt. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy határoló dobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy határoló dobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható (logikai) dobozba helyezi, amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. Egy keretelt objektum például operátor emulátorként szolgálhat, vonalbeállító ponttal vagy anélkül, sorok törésének pontjaként, vagy úgy csoportosítható, hogy ne engedje a sortöréseket a belsejében. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Az elem aljára vonalat helyez. |

### Példák

Példa:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
```

### Lásd még

* osztály [BaseScript](../basescript)
* interfész [IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->