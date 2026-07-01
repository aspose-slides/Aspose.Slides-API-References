---
title: MathematicalText
second_title: Riferimento API Aspose.Sildes per .NET
description: Testo matematico
type: docs
weight: 9040
url: /it/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText classe

Testo matematico

```csharp
public sealed class MathematicalText : MathElementBase, IMathematicalText
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MathematicalText](mathematicaltext#constructor)() | Costruttore predefinito (crea valore String.Empty) |
| [MathematicalText](mathematicaltext#constructor_1)(char) | Crea MathText con un singolo simbolo |
| [MathematicalText](mathematicaltext#constructor_2)(string) | Crea MathematicalText dal testo |
| [MathematicalText](mathematicaltext#constructor_3)(string, IPortionFormat) | Crea MathematicalText dal testo e dalle impostazioni di formato |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Format](../../aspose.slides.mathtext/mathematicaltext/format) { get; } | Proprietà di formattazione del testo |
| [Value](../../aspose.slides.mathtext/mathematicaltext/value) { get; set; } | Valore del testo |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Imposta un accento (un carattere nella parte superiore di questo elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Applica la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Applica la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Applica la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Applica la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Applica la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Inserisce un elemento matematico tra parentesi |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Inserisce un elemento matematico nei caratteri specificati come parentesi o altri caratteri di delimitazione |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Applica una funzione di un argomento usando questa istanza come nome della funzione |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Applica una funzione di un argomento usando questa istanza come nome della funzione |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Inserisce questo elemento in un gruppo usando una graffa inferiore |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Inserisce questo elemento in un gruppo usando un carattere di raggruppamento come graffa inferiore o altro |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Prende l'integrale senza limiti |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prende l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prende l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prende l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prende l'integrale |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Unisce un elemento matematico e forma un blocco matematico |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Unisce un testo matematico e forma un blocco matematico |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operatore N-ario |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crea un operatore N-ario |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Imposta una barra nella parte superiore di questo elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specifica la radice matematica del grado dato dall'argomento specificato |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specifica la radice matematica del grado dato dall'argomento specificato |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Prende il limite inferiore |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Prende il limite inferiore |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea apice inferiore |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea apice inferiore |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea apice inferiore e superiore a sinistra |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea apice inferiore e superiore a sinistra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea apice inferiore e superiore a destra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea apice inferiore e superiore a destra |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea apice superiore |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea apice superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Prende il limite superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Prende il limite superiore |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Inserisce questo elemento in una cornice |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Inserisce questo elemento in una cornice |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Inserisce questo elemento in una scatola non visiva (gruppamento logico) utilizzata per raggruppare componenti di un'equazione o di altro testo matematico. Un oggetto incorniciato può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di riga o essere raggruppato in modo da non permettere interruzioni di riga all'interno. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Inserisce in una matrice verticale |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Imposta una barra nella parte inferiore di questo elemento |

### Esempi

Esempio:

```csharp
[C#]
MathematicalText mathText = new MathematicalText("x+y");
```

### Vedi anche

* classe [MathElementBase](../mathelementbase)
* interfaccia [IMathematicalText](../imathematicaltext)
* spazio dei nomi [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->