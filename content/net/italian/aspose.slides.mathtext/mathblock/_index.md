---
title: MathBlock
second_title: Aspose.Sildes per la documentazione API .NET
description: Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria riga. Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da un blocco matematico.
type: docs
weight: 8590
url: /it/aspose.slides.mathtext/mathblock/
---
## MathBlock classe

Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria riga. Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule sono rappresentate da un blocco matematico.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Inizializza una nuova istanza della classe MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Crea un nuovo blocco matematico e inserisce gli elementi specificati al suo interno. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Crea un nuovo blocco matematico e inserisce l'elemento specificato al suo interno. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Restituisce il numero di elementi matematici figlio realmente contenuti nella collezione. Solo lettura Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Restituisce false perché la collezione di elementi figlio può essere modificata. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Ottiene o imposta IMathElement all'indice specificato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Imposta un segno diacritico (un carattere sopra questo elemento). |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Aggiunge un elemento matematico alla fine della collezione. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Utilizza la funzione specificata usando questa istanza come argomento. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Utilizza la funzione specificata usando questa istanza come argomento. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Utilizza la funzione specificata usando questa istanza come argomento. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Utilizza la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Utilizza la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Rimuove tutti gli elementi dalla collezione. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Determina se la collezione contiene un valore specifico. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Copia nell'array specificato. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Delimita gli elementi figlio con il carattere separatore (senza le parentesi). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una frazione con questo numeratore e il denominatore specificato. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una frazione con questo numeratore e il denominatore specificato. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Racchiude un elemento matematico tra parentesi. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Racchiude gli elementi figlio di questo blocco nei caratteri specificati, ad esempio parentesi o altri caratteri di inquadratura. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Racchiude gli elementi figlio di questo blocco nei caratteri specificati, ad esempio parentesi o altri come inquadratura e li delimita con un carattere separatore. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Utilizza una funzione di un argomento usando questa istanza come nome della funzione. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Utilizza una funzione di un argomento usando questa istanza come nome della funzione. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Ottiene gli elementi figli. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Posiziona questo elemento in un gruppo usando una parentesi graffa inferiore. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento, come una parentesi graffa inferiore o un altro. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Determina l'indice di un elemento matematico specifico nella collezione. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Inserisce un MathElement nella collezione all'indice specificato. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Restituisce l'integrale senza limiti. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Restituisce l'integrale. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Restituisce l'integrale. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Restituisce l'integrale. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Restituisce l'integrale. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Unisce un elemento matematico a questo blocco matematico. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Unisce un testo matematico a questo blocco matematico. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Unisce un altro blocco matematico a questo. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operatore N-ario. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crea un operatore N-ario. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Imposta una barra in alto di questo elemento. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Rimuove la prima occorrenza di un oggetto specifico dalla collezione. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Rimuove l'elemento all'indice specificato nella collezione. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Restituisce il limite inferiore. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Restituisce il limite inferiore. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea un pedice. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea un pedice. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea pedice e apice a sinistra. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea pedice e apice a sinistra. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea pedice e apice a destra. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea pedice e apice a destra. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea un apice. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea un apice. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Restituisce il limite superiore. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Restituisce il limite superiore. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Posiziona questo elemento in un riquadro bordato. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Posiziona questo elemento in un riquadro bordato. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Posiziona questo elemento in una casella non visiva (raggruppamento logico) utilizzata per raggruppare componenti di un'equazione o di un'altra istanza di testo matematico. Un oggetto racchiuso può (ad esempio) servire da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di linea o essere raggruppato in modo da non consentire interruzioni di linea al suo interno. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Dispone gli elementi figlio in un array verticale. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Imposta una barra in basso di questo elemento. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Salva il contenuto di questo [`MathBlock`](../mathblock) come MathML. |

### Esempi

Esempio:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Vedi anche

* classe [MathElementBase](../mathelementbase)
* interfaccia [IMathBlock](../imathblock)
* spazio dei nomi [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->