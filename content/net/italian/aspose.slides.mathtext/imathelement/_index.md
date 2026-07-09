---
title: IMathElement
second_title: Riferimento API Aspose.Sildes per .NET
description: Interfaccia base di qualsiasi elemento matematico, frazione, testo matematico, funzione, espressione con più elementi, ecc
type: docs
weight: 8230
url: /it/aspose.slides.mathtext/imathelement/
---
## Interfaccia IMathElement

Interfaccia base di qualsiasi elemento matematico: frazione, testo matematico, funzione, espressione con più elementi, ecc

```csharp
public interface IMathElement
```

## Metodi

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Imposta un segno di accento (un carattere nella parte superiore di questo elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Applica la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Applica la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Applica la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Applica la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Applica la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Racchiude un elemento matematico tra parentesi |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Racchiude questo elemento nei caratteri specificati, come parentesi o altri caratteri di inquadramento |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Applica una funzione di un argomento usando questa istanza come nome della funzione |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Applica una funzione di un argomento usando questa istanza come nome della funzione |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Recupera gli elementi figli |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Posiziona questo elemento in un gruppo usando una parentesi graffa inferiore |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento, come una parentesi graffa inferiore o altro |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Applica l'integrale senza limiti |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMMathElement, IMathElement) | Applica l'integrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Applica l'integrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Applica l'integrale |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Applica l'integrale |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Unisce un elemento matematico e forma un blocco matematico |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Unisce un testo matematico e forma un blocco matematico |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operatore N-ario |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | Crea un operatore N-ario |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Imposta una barra sulla parte superiore di questo elemento |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Specifica la radice matematica del grado indicato a partire dall'argomento specificato. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Specifica la radice matematica del grado indicato a partire dall'argomento specificato. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Applica il limite inferiore |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Applica il limite inferiore |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Crea pedice |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Crea pedice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea pedice e apice a destra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Crea pedice e apice a destra |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Crea apice |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Crea apice |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Applica il limite superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Applica il limite superiore |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Posiziona questo elemento in un riquadro |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Posiziona questo elemento in un riquadro |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Posiziona questo elemento in un riquadro non visivo (raggruppamento logico) utilizzato per raggruppare componenti di un'equazione o altra istanza di testo matematico. Un oggetto riquadrato può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Inserisce in un array verticale |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Imposta una barra nella parte inferiore di questo elemento |

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