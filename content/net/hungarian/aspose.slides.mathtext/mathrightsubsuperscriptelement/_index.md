---
title: MathRightSubSuperscriptElement
second_title: Aspose.Sildes .NET API referencia
description: Meghatározza az al-felső index objektumot, amely egy alapból és az alap jobb oldalára helyezett alsó indexből és felső indexből áll.
type: docs
weight: 8940
url: /hu/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement osztály

Meghatározza az al/felső index objektumot, amely egy alapból és az alap jobb oldalára elhelyezett alsó indexből és felső indexből áll.

```csharp
public sealed class MathRightSubSuperscriptElement : BaseScript, IMathRightSubSuperscriptElement
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | Új példányt hoz létre a MathRightSubSuperscriptElement osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlignScripts](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts) { get; set; } | Megadja az alsó index/felső index igazítását. Ha igaz, az alsó index és a felső index vízszintesen egymáshoz igazítva vannak. Ha hamis, az alap alakjához vannak illesztve. Alapértelmezett érték: hamis. |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Alap argumentum |
| [Subscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript) { get; } | Alsó index argumentum |
| [Superscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript) { get; } | Felső index argumentum |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Akként jelöl egy ékezetet (egy karaktert az elem tetején). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt vesz, ahol ez az példány argumentumként szolgál. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt vesz, ahol ez az példány argumentumként szolgál. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt vesz, ahol ez az példány argumentumként szolgál. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt vesz, ahol ez az példány argumentumként és a megadott további argumentumként szolgál. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt vesz, ahol ez az példány argumentumként és a megadott további argumentumként szolgál. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz a megadott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Egy matematikai elemet zár zárójelbe. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Egy matematikai elemet a megadott karakterekkel (például zárójelekkel vagy más karakterekkel) keretez. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Argumentumfüggvényt vesz, ahol ez az példány a függvény neve. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Argumentumfüggvényt vesz, ahol ez az példány a függvény neve. |
| [GetChildren](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/getchildren)() | Gyermekelemeket lekér. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi alul lévő kapcsos zárójel használatával. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakter, például alul lévő kapcsos zárójel vagy más karakter használatával. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Integrált vesz korlátok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrált vesz. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrált vesz. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrált vesz. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrált vesz. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és matematikai blokkoká alakítja. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és matematikai blokkoká alakítja. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-áris operátort hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-áris operátort hoz létre. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Felső vonalat helyez az elem tetejére. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a matematikai gyököt a megadott fokszámmal a konkrét argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a matematikai gyököt a megadott fokszámmal a konkrét argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Balra hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Balra hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobbra hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobbra hoz létre alsó és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. A dobozos objektum például szolgálhat operátor emulátorként, sorvége jelként vagy úgy csoportosítható, hogy ne engedjen sortörést. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömbbe helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Alsó vonalat helyez az elem aljára. |

### Példák

```csharp
[C#]
MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### Lásd még

* osztály [BaseScript](../basescript)
* interfész [IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->