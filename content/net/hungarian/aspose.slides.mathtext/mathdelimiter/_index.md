---
title: MathDelimiter
second_title: Aspose.Sildes .NET API referencia
description: Megadja a delimiter objektumot, amely nyitó és záró karakterekből, például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak, áll, valamint egy vagy több matematikai elemet tartalmaz, amelyeket egy meghatározott karakterrel választanak el. Példák: 2 2x7C2
type: docs
weight: 8630
url: /hu/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter osztály

Megadja a delimitter objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz belül, amelyeket egy megadott karakterrel választanak el. Példák: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | Inicializálja a MathDelimiter-t a megadott elemmel, mint egyetlen alapargumentummal |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | Egy vagy több matematikai elem, amely a delimitter karakterekkel van elválasztva |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | A Delimiter Beginning Character meghatározza a kezdeti, vagy nyitó, delimitter karaktert. A matematikai delimitterek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: '('. |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | Meghatározza a delimitterek alakját a delimitter objektumban. Ha a MathDelimiterShape.Centered, a delimitterek a matematikai szöveg tengelye köré középre helyeződnek, és a tartalom teljes magasságához igazodnak. Ha a MathDelimiterShape.Match, magasságuk és alakjuk pontosan a tartalomhoz igazodik. |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | A Delimiter Ending Character meghatározza a záró, vagy befejező, delimitter karaktert. A matematikai delimitterek olyan körülhatároló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | Meghatározza a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a delimitterek függőlegesen nőnek, hogy megfeleljenek az operandus magasságának. Alapértelmezett érték: true. |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | A Delimiter Separator Character meghatározza azt a karaktert, amely elválasztja az argumentumokat a delimitter objektumban. Alapértelmezett: '&#x7C;'. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Beállít egy akcentusjelet (karaktert az elem tetején) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Megadott függvényt hív meg, amelynek argumentuma ez a példány |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Megadott függvényt hív meg, amelynek argumentuma ez a példány |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Megadott függvényt hív meg, amelynek argumentuma ez a példány |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Megadott függvényt hív meg, amelynek argumentuma ez a példány, és egy megadott további argumentum is |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Megadott függvényt hív meg, amelynek argumentuma ez a példány, és egy megadott további argumentum is |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | Elválasztja az argumentumokat a megadott delimitter karakterrel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Törtet hoz létre ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Törtet hoz létre ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Megadott típusú törtet hoz létre ezzel a számlálóval és a megadott nevezővel |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Megadott típusú törtet hoz létre ezzel a számlálóval és a megadott nevezővel |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Egy matematikai elemet zárójelek közé tesz |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | Egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretez |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Megadott argumentumfüggvényt alkalmaz, amelynek függvényneve ez a példány |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Megadott argumentumfüggvényt alkalmaz, amelynek függvényneve ez a példány |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | Lekéri a gyermekelemeket |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Az elemet egy csoportba helyezi, alsó kapcsos zárójel használatával |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Az elemet egy csoportba helyezi a megadott csoportosító karakterrel, például alsó kapcsos záróval vagy más karakterrel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Integrált vesz fel határok nélkül |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrált vesz fel |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrált vesz fel |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Összekapcsol egy matematikai elemet és blokkot hoz létre |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Összekapcsol egy matematikai szöveget és blokkot hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-áris operátort hoz létre |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-áris operátort hoz létre |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Sávot helyez az elem tetejére |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Megadja a megadott fokú matematikai gyököt a megadott argumentumból |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alsó határt vesz fel |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alsó határt vesz fel |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alsó indexet hoz létre |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alsó indexet hoz létre |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Balra helyezi el az alsó és felső indexet |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Balra helyezi el az alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Jobbra helyezi el az alsó és felső indexet |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Jobbra helyezi el az alsó és felső indexet |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Felső indexet hoz létre |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Felső indexet hoz létre |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Felső határt vesz fel |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Felső határt vesz fel |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Az elemet keretdobozba helyezi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Az elemet keretdobozba helyezi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Az elemet egy nem látható dobozba (logikai csoportosítás) helyezi, amelyet egy egyenlet vagy más matematikai szöveg komponenseinek csoportosítására használnak. Egy ilyen doboz például operátor emulátorként szolgálhat igazítási ponttal vagy anélkül, sortöréshelyként funkcionálhat, vagy úgy csoportosítható, hogy ne engedje a sortöréseket a belsejében. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Függőleges tömböt helyez el |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Sávot helyez az elem aljára |

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