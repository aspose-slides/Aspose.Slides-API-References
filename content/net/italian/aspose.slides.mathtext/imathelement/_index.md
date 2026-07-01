---
title: IMathElement
second_title: Riferimento API Aspose.Sildes per .NET
description: Interfaccia di base di qualsiasi elemento matematico, frazione, testo matematico, funzione, espressione con più elementi, ecc
type: docs
weight: 8210
url: /it/aspose.slides.mathtext/imathelement/
---
## Interfaccia IMathElement

Interfaccia base di qualsiasi elemento matematico: frazione, testo matematico, funzione, espressione con più elementi ecc.

```csharp
public interface IMathElement
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Imposta un segno di accento (un carattere sulla parte superiore di questo elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Utilizza la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Utilizza la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Utilizza la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Utilizza la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Utilizza la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Racchiude un elemento matematico tra parentesi |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Racchiude questo elemento nei caratteri specificati, come parentesi o altri caratteri come cornice |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Utilizza una funzione di un argomento usando questa istanza come nome della funzione |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Utilizza una funzione di un argomento usando questa istanza come nome della funzione |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Recupera gli elementi figli |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Posiziona questo elemento in un gruppo usando una graffa inferiore |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento, come una graffa inferiore o altro |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Ottiene l'integrale senza limiti |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Ottiene l'integrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Ottiene l'integrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Ottiene l'integrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Ottiene l'integrale |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Unisce un elemento matematico e forma un blocco matematico |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Unisce un testo matematico e forma un blocco matematico |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operatore N-ario |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Crea un operatore N-ario |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Imposta una barra sulla parte superiore di questo elemento |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Specifica la radice matematica del grado indicato dall'argomento specificato. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Specifica la radice matematica del grado indicato dall'argomento specificato. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Ottiene il limite inferiore |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Ottiene il limite inferiore |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Crea un pedice |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Crea un pedice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea pedice e apice a destra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Crea pedice e apice a destra |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Crea un apice |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Crea un apice |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Ottiene il limite superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Ottiene il limite superiore |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Posiziona questo elemento in una casella con bordo |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Posiziona questo elemento in una casella con bordo |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Posiziona questo elemento in una casella non visiva (raggruppamento logico) che viene utilizzata per raggruppare componenti di un'equazione o di altro testo matematico. Un oggetto racchiuso può (ad esempio) servire come emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di linea o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Inserisce in un array verticale |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Imposta una barra sulla parte inferiore di questo elemento |

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