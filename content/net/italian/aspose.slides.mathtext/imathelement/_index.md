---
title: IMathElement
second_title: Riferimento API di Aspose.Sildes per .NET
description: Interfaccia di base di qualsiasi elemento matematico: frazione, testo matematico, funzione, espressione con più elementi, ecc
type: docs
weight: 8250
url: /it/aspose.slides.mathtext/imathelement/
---
## Interfaccia IMathElement

Interfaccia base di qualsiasi elemento matematico: frazione, testo matematico, funzione, espressione con più elementi, ecc.

```csharp
public interface IMathElement
```

## Metodi

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Imposta un segno diacritico (un carattere sopra questo elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Prende la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Prende la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Prende la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Prende la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Racchiude un elemento matematico tra parentesi |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Racchiude questo elemento nei caratteri specificati, come parentesi o altri caratteri di inquadratura |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Prende una funzione di un argomento usando questa istanza come nome della funzione |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Ottiene gli elementi figli |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Inserisce questo elemento in un gruppo usando una graffa inferiore |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Inserisce questo elemento in un gruppo usando un carattere di raggruppamento come una graffa inferiore o altro |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Prende l'integrale senza limiti |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Prende l'integrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Prende l'integrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Prende l'integrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Prende l'integrale |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Unisce un elemento matematico e forma un blocco matematico |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Unisce un testo matematico e forma un blocco matematico |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operatore n-ario |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Crea un operatore n-ario |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Imposta una barra sopra questo elemento |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Specifica la radice matematica del grado dato dall'argomento specificato |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Specifica la radice matematica del grado dato dall'argomento specificato |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Prende il limite inferiore |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Prende il limite inferiore |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Crea un pedice |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Crea un pedice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea pedice e apice a destra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Crea pedice e apice a destra |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Crea un apice |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Crea un apice |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Prende il limite superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Prende il limite superiore |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Inserisce questo elemento in una casella con bordi |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Inserisce questo elemento in una casella con bordi |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Inserisce questo elemento in una casella non visuale (raggruppamento logico) usata per raggruppare componenti di un'equazione o di altro testo matematico. Un oggetto incorniciato può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, servire come punto di interruzione di riga o essere raggruppato per non consentire interruzioni di riga al suo interno. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Inserisce in una matrice verticale |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Imposta una barra alla base di questo elemento |

### Esempi

Esempio:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Vedi anche

* spazio dei nomi [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->