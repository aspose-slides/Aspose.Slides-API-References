---
title: MathBox
second_title: Riferimento API di Aspose.Sildes per .NET
description: Specifica il packaging logico (incapsulamento) di un elemento matematico. Per esempio, un oggetto incapsulato può servire da emulatore di operatore con o senza un punto di allineamento, fungere da punto di interruzione di riga o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. Per esempio, l'operatore dovrebbe essere incapsulato per prevenire interruzioni di riga.
type: docs
weight: 8650
url: /it/aspose.slides.mathtext/mathbox/
---
## MathBox classe

Specifica il packaging (incapsulamento) logico di un elemento matematico. Ad esempio, un oggetto incapsulato può fungere da emulatore di operatore con o senza un punto di allineamento, fungere da punto di interruzione di riga o essere raggruppato per non consentire interruzioni di riga al suo interno. Ad esempio, l'operatore "==" dovrebbe essere incapsulato per evitare interruzioni di riga.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Inizializza MathBox con l'elemento specificato come argomento |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Quando è true, questo emulatore di operatore funge da punto di allineamento; cioè, i punti di allineamento designati in altre equazioni possono essere allineati a esso. Predefinito: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Argomento base |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differenziale Quando è true, la casella agisce come un differenziale (ad es., 𝑑𝑥 in un integrando) e riceve la spaziatura orizzontale appropriata per il differenziale matematico. Predefinito: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Interruzione esplicita indica se è presente un'interruzione di riga all'inizio dell'oggetto Box, in modo che la linea si avvolga all'inizio dell'oggetto box. Specifica il numero dell'operatore sulla riga precedente del testo matematico che deve essere usato come punto di allineamento per la riga corrente del testo matematico; valori possibili: 1..255. Predefinito: 0 (nessuna interruzione esplicita) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | Nessuna interruzione Questa proprietà specifica la proprietà "unbreakable" sull'oggetto box. Quando è true, non è possibile inserire interruzioni di riga all'interno del box. Questo può essere importante per gli emulatori di operatore che consistono in più di un operatore binario. Quando questo elemento non è specificato, le interruzioni possono verificarsi all'interno del box. Predefinito: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Emulatore di operatore. Quando è true, il box e i suoi contenuti si comportano come un unico operatore e ne ereditano le proprietà. Ciò significa, per esempio, che il carattere può servire come punto di interruzione di riga e può essere allineato ad altri operatori. Gli emulatori di operatore sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Imposta un segno diacritico (un carattere sulla parte superiore di questo elemento) |
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
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri, come inquadratura |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Esegue una funzione di un argomento usando questa istanza come nome della funzione |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Esegue una funzione di un argomento usando questa istanza come nome della funzione |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Ottiene gli elementi figli |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Inserisce questo elemento in un gruppo usando una parentesi graffa inferiore |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Inserisce questo elemento in un gruppo usando un carattere di raggruppamento, come una parentesi graffa inferiore o altro |
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
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specifica la radice matematica del grado dato a partire dall'argomento specificato. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specifica la radice matematica del grado dato a partire dall'argomento specificato. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Inserisce questo elemento in una casella con bordo |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Inserisce questo elemento in una casella con bordo |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Inserisce questo elemento in una casella non visiva (raggruppamento logico) che è usata per raggruppare componenti di un'equazione o altra istanza di testo matematico. Un oggetto incapsulato può (ad esempio) servire da emulatore di operatore con o senza punto di allineamento, servire da punto di interruzione di riga, o essere raggruppato per non consentire interruzioni di riga al suo interno. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Inserisce in un array verticale |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Imposta una barra nella parte inferiore di questo elemento |

### Esempi

Example:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Vedi anche

* classe [MathElementBase](../mathelementbase)
* interfaccia [IMathBox](../imathbox)
* spazio dei nomi [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->