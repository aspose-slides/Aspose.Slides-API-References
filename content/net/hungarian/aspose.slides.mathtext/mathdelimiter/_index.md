---
title: MathDelimiter
second_title: Aspose.Sildes .NET API hivatkozás
description: Megadja a határoló objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, valamint egy vagy több matematikai elemet tartalmaz, amelyeket egy megadott karakter választ el. Példák: 2 2x7C2
type: docs
weight: 8670
url: /hu/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter osztály

Meghatározza a határoló objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, valamint egy vagy több matematikai elemet tartalmaz, amelyeket egy megadott karakter választ el. Példák: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Inicializálja a MathDelimiter objektumot a megadott elemmel egyetlen alapértelmezett argumentumként |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Egy vagy több matematikai elem, amelyet határoló karakterek választanak el |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | A Delimiter Beginning Character megadja a kezdő, vagy nyitó, határoló karaktert. A matematikai határolók a zárójelek, szögletes zárójelek és kapcsos zárójelekhez hasonló körülvett karakterek. Alapértelmezett: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Meghatározza a határolók alakját a határoló objektumban. Ha a MathDelimiterShape.Centered, a határolók a matematikai szöveg tengelye köré középre vannak igazítva, és a tartalmuk teljes magasságához igazíthatók. Ha a MathDelimiterShape.Match, magasságuk és alakjuk pontosan a tartalomhoz igazodik. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | A Delimiter Ending Character megadja a záró, vagy lezáró, határoló karaktert. A matematikai határolók a zárójelek, szögletes zárójelek és kapcsos zárójelekhez hasonló körülvett karakterek. Alapértelmezett: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Megadja a BeginningCharacter, SeparatorCharacter és EndingCharacter növekedését. Ha true, a határolók függőlegesen nőnek, hogy megfeleljenek az operandus magasságának. Az alapértelmezett érték true. |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | A Delimiter Separator Character megadja azt a karaktert, amely elválasztja az argumentumokat a határoló objektumban. Alapértelmezett: '&#x7C;'. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentus jelet (egy karaktert az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Végrehajt egy megadott függvényt, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Végrehajt egy megadott függvényt, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Végrehajt egy megadott függvényt, amely ezt a példányt használja argumentumként |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Végrehajt egy megadott függvényt, amely ezt a példányt használja argumentumként, valamint a megadott további argumentumot |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Végrehajt egy megadott függvényt, amely ezt a példányt használja argumentumként, valamint a megadott további argumentumot |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Határolja az argumentumokat a megadott határoló karakterrel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehozza a törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy megadott típusú törtet ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Zár egy matematikai elemet zárójelek közé |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Zár egy matematikai elemet a megadott karakterek közé, például zárójelek vagy más keretező karakterek |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Alkalmaz egy függvényt, amely ezt a példányt használja függvényneveként |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Alkalmaz egy függvényt, amely ezt a példányt használja függvényneveként |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Lekéri a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi egy csoportosító karakterrel, például alsó kapcsos zárójellel vagy más karakterrel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Végrehajt egy integrált határértékek nélkül |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Végrehajt egy integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Végrehajt egy integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Végrehajt egy integrált |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Végrehajt egy integrált |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet, és egy matematikai blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget, és egy matematikai blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-áris operátort |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-áris operátort |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Beállít egy vonalat az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Lekéri az alsó határt |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Lekéri az alsó határt |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Létrehozza az alsó indexet |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Létrehozza az alsó indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Létrehozza a felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Létrehozza a felső indexet |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Lekéri a felső határt |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Lekéri a felső határt |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amely egyenlet vagy más matematikai szöveg komponenseinek csoportosítására szolgál. Egy dobozba helyezett objektum például használható operátor emulátorként igazítási ponttal vagy anélkül, sorvége jelként, vagy úgy csoportosítható, hogy ne engedje a sortöréseket belül. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Elhelyez egy függőleges tömböt |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Beállít egy vonalat az elem aljára |

### Példák

Példa:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### Lásd még

* osztály [MathElementBase](../mathelementbase)
* interfész [IMathDelimiter](../imathdelimiter)
* névtér [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->