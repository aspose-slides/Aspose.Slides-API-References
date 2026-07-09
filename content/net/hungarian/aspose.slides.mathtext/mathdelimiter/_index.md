---
title: MathDelimiter
second_title: Aspose.Sildes .NET API referencia
description: Meghatározza a határoló objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz, amelyeket egy megadott karakter választ el. Példák: 2 2x7C2
type: docs
weight: 8650
url: /hu/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter osztály

Meghatározza a határoló objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz, amelyeket egy megadott karakter elválaszt. Példák: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Initializes MathDelimiter with the specified element as single base argument |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Egy vagy több matematikai elem, amelyet a határoló karakterek választanak el |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó, határoló karaktert. A matematikai határolók olyan körülölelő karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Meghatározza a határolók alakját a határoló objektumban. Ha a MathDelimiterShape.Centered, a határolók a matematikai szöveg tengelye köré középre helyezkednek, és a tartalom teljes magasságához igazodnak. Ha a MathDelimiterShape.Match, magasságuk és alakjuk pontosan a tartalomhoz igazodik. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | A Delimiter Ending Character meghatározza a befejező, vagy záró, határoló karaktert. A matematikai határolók olyan körülölelő karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Meghatározza a BeginningCharacter, SeparatorCharacter és EndingCharacter növekedését. Ha igaz, a határolók függőlegesen növekednek, hogy illeszkedjenek az operandus magasságához. Alapértelmezett érték: true |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a határoló objektumban. Alapértelmezett: '&#x7C;'. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentusjelet (egy karakter az elem tetején). |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt használ, ahol ez a példány az argumentum. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt használ, ahol ez a példány az argumentum. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt használ, ahol ez a példány az argumentum. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt használ, ahol ez a példány az első argumentum, és egy megadott további argumentumot is átad. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt használ, ahol ez a példány az első argumentum, és egy megadott további argumentumot ad át. |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Az argumentumokat a megadott határoló karakterrel választja el. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Létrehoz egy törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Létrehoz egy meghatározott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Létrehoz egy meghatározott típusú törtet ezzel a számlálóval és a megadott nevezővel. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Egy matematikai elemet zárójelek közé helyez. |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Egy matematikai elemet a megadott karakterek közé helyez, például zárójelek vagy egyéb keretező karakterek. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Függvényt vesz fel egy argumentummal, ahol ez a példány a függvény neve. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Függvényt vesz fel egy argumentummal, ahol ez a példány a függvény neve. |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Lekéri a gyermekelemeket. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi, egy alsó kapcsos zárójel segítségével. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi, egy csoportosító karakter, például alsó kapcsos zárójel vagy más karakter használatával. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Integrált vesz fel korlátok nélkül. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrált vesz fel. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrált vesz fel. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrált vesz fel. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrált vesz fel. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Egy matematikai elemet egyesít és matematikai blokkot hoz létre. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematikai szöveget egyesít és matematikai blokkot hoz létre. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Létrehoz egy N-értelmű operátort. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Létrehoz egy N-értelmű operátort. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Beállít egy vonalat az elem tetején. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz fel. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz fel. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Bal oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Bal oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobb oldalon hoz létre alsó és felső indexet. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobb oldalon hoz létre alsó és felső indexet. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz fel. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz fel. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet egy keretdobozba helyezi. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet egy keretdobozba helyezi (több bool paraméterrel). |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amely egyenlet vagy más matematikai szöveg összetevőit csoportosítja. Egy ilyen doboz (például) operátor emulátorként szolgálhat igazolási ponttal vagy anélkül, sortörés pontként funkcionálhat, vagy úgy csoportosítható, hogy ne engedélyezi a sortöréseket belül. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges mátrixba helyezi. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Beállít egy vonalat az elem alján. |

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