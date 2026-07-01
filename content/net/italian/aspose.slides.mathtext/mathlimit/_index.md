---
title: MathLimit
second_title: Riferimento API Aspose.Sildes per .NET
description: Specifica l'oggetto Limit composto da testo sulla linea di base e testo di dimensioni ridotte immediatamente sopra o sotto di esso.
type: docs
weight: 8800
url: /it/aspose.slides.mathtext/mathlimit/
---
## MathLimit classe

Specifica l'oggetto Limit, costituito da testo sulla linea di base e testo di dimensioni ridotte immediatamente sopra o sotto di esso.

```csharp
public sealed class MathLimit : MathElementBase, IMathLimit
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MathLimit](mathlimit#constructor)(IMathElement, IMathElement) | Inizializza una nuova istanza della classe MathLimit con limite inferiore |
| [MathLimit](mathlimit#constructor_1)(IMathElement, IMathElement, bool) | Inizializza una nuova istanza della classe MathLimit. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathlimit/base) { get; } | Argomento di base |
| [Limit](../../aspose.slides.mathtext/mathlimit/limit) { get; } | Argomento limite |
| [UpperLimit](../../aspose.slides.mathtext/mathlimit/upperlimit) { get; set; } | Specifica limite superiore o inferiore |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Imposta un segno di accento (un carattere sulla parte superiore di questo elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Prende la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Prende la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Prende la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Racchiude un elemento matematico tra parentesi |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri di inquadratura |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [GetChildren](../../aspose.slides.mathtext/mathlimit/getchildren)() | Ottiene gli elementi figli |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Colloca questo elemento in un gruppo usando una graffa inferiore |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Colloca questo elemento in un gruppo usando un carattere di raggruppamento, come una graffa inferiore o altro |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Prende l'integrale senza limiti |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Prende l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Prende l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prende l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Prende l'integrale |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Unisce un elemento matematico e forma un blocco matematico |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Unisce un testo matematico e forma un blocco matematico |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operatore N-ario |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crea un operatore N-ario |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Imposta una barra sulla parte superiore di questo elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Prende il limite inferiore |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Prende il limite inferiore |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea pedice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea pedice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea pedice e apice a destra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea pedice e apice a destra |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea apice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea apice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Prende il limite superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Prende il limite superiore |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Colloca questo elemento in un riquadro di bordo |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Colloca questo elemento in un riquadro di bordo |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Colloca questo elemento in una casella non visiva (raggruppamento logico) utilizzata per raggruppare componenti di un'equazione o altro testo matematico. Un oggetto racchiuso può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di linea, o essere raggruppato in modo da non consentire interruzioni di linea al suo interno. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Inserisce in una serie verticale |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Imposta una barra sulla parte inferiore di questo elemento |

### Esempi

Esempio:

```csharp
[C#]
MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("𝑛→∞"));
```

### Vedi anche

* classe [MathElementBase](../mathelementbase)
* interfaccia [IMathLimit](../imathlimit)
* spazio dei nomi [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->