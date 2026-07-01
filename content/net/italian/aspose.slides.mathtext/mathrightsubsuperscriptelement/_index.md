---
title: MathRightSubSuperscriptElement
second_title: Riferimento API Aspose.Sildes per .NET
description: Specifica l'oggetto Sub-Superscript, che è composto da una base e da un pedice e un apice posizionati a destra della base.
type: docs
weight: 8940
url: /it/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement classe

Specifica l'oggetto Sub-Superscript, che è composto da una base e da un pedice e un apice posizionati a destra della base.

```csharp
public sealed class MathRightSubSuperscriptElement : BaseScript, IMathRightSubSuperscriptElement
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | Inizializza una nuova istanza della classe MathRightSubSuperscriptElement. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlignScripts](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts) { get; set; } | Specifica l'allineamento di pedice/apice. Quando true, pedice e apice sono allineati orizzontalmente tra loro. Quando false, sono adattati alla forma della base. Il valore predefinito è false. |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Argomento base |
| [Subscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript) { get; } | Argomento del pedice |
| [Superscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript) { get; } | Argomento dell'apice |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Imposta un segno di accento (un carattere nella parte superiore di questo elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Esegue la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Esegue la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Esegue la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Esegue la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Esegue la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Racchiude un elemento matematico tra parentesi |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri come cornice |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Esegue una funzione di un argomento usando questa istanza come nome della funzione |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Esegue una funzione di un argomento usando questa istanza come nome della funzione |
| [GetChildren](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/getchildren)() | Ottiene gli elementi figli |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Posiziona questo elemento in un gruppo usando una parentesi graffa inferiore |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento, come una parentesi graffa inferiore o altro |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Esegue l'integrale senza limiti |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Esegue l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Esegue l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Esegue l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Esegue l'integrale |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Unisce un elemento matematico e forma un blocco matematico |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Unisce un testo matematico e forma un blocco matematico |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operatore N-ario |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crea un operatore N-ario |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Imposta una barra nella parte superiore di questo elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Restituisce il limite inferiore |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Restituisce il limite inferiore |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea un pedice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea un pedice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea pedice e apice a destra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea pedice e apice a destra |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea un apice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea un apice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Restituisce il limite superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Restituisce il limite superiore |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Posiziona questo elemento in una casella con bordi |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Posiziona questo elemento in una casella con bordi |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Posiziona questo elemento in una casella non visiva (raggruppamento logico) utilizzata per raggruppare componenti di un'equazione o di altre istanze di testo matematico. Un oggetto incapsulato può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Inserisce in un array verticale |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Imposta una barra nella parte inferiore di questo elemento |

### Esempi

Esempio:

```csharp
[C#]
MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### Vedi anche

* classe [BaseScript](../basescript)
* interfaccia [IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement)
* spazio dei nomi [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->