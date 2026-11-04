---
title: MathBlock
second_title: Riferimento API Aspose.Sildes per .NET
description: Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria riga. Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da MathBlock.
type: docs
weight: 8610
url: /it/aspose.slides.mathtext/mathblock/
---
## MathBlock classe

Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria riga. Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule sono rappresentate da blocco matematico.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MathBlock](mathblock#constructor)() | Inizializza una nuova istanza della classe MathBlock. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Crea un nuovo blocco matematico e inserisce gli elementi specificati al suo interno |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Crea un nuovo blocco matematico e inserisce l'elemento specificato al suo interno |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Restituisce il numero di elementi matematici figlio effettivamente contenuti nella raccolta. Int32 sola lettura. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Restituisce false perché la raccolta di elementi figlio può essere modificata. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Ottiene o imposta IMathElement all'indice specificato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Imposta un segno di accento (un carattere nella parte superiore di questo elemento) |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Aggiunge un elemento matematico alla fine della raccolta. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Esegue la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Esegue la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Esegue la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Esegue la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Esegue la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Rimuove tutti gli elementi dalla raccolta. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Determina se la raccolta contiene un valore specifico. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Copia nell'array specificato. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Delimita gli elementi figlio con il carattere separatore (senza le parentesi) |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Racchiude un elemento matematico tra parentesi |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come parentesi o altri caratteri, come cornice |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come parentesi o altri, come cornice e li delimita con un carattere separatore |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Esegue una funzione di un argomento usando questa istanza come nome della funzione |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Esegue una funzione di un argomento usando questa istanza come nome della funzione |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Ottiene gli elementi figlio |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Posiziona questo elemento in un gruppo usando una parentesi graffa inferiore |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Posiziona questo elemento in un gruppo usando un carattere di raggruppamento, come parentesi graffa inferiore o altro. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Determina l'indice di un elemento matematico specifico nella raccolta. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Inserisce un MathElement nella raccolta all'indice specificato. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Esegue l'integrale senza limiti |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Esegue l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Esegue l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Esegue l'integrale |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Esegue l'integrale |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Unisce un elemento matematico con questo blocco matematico |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Unisce un testo matematico con questo blocco matematico |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Unisce un altro blocco matematico a questo |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | Crea un operatore N-ario |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | Crea un operatore N-ario |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Imposta una barra nella parte superiore di questo elemento |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Specifica la radice matematica del grado dato dall'argomento specificato. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Rimuove l'elemento all'indice specificato della raccolta. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Imposta il limite inferiore |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Imposta il limite inferiore |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea un apice inferiore |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea un apice inferiore |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea apice inferiore e apice superiore a sinistra |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea apice inferiore e apice superiore a sinistra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea apice inferiore e apice superiore a destra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea apice inferiore e apice superiore a destra |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea apice superiore |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea apice superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Imposta il limite superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Imposta il limite superiore |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Posiziona questo elemento in una scatola con bordo |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Posiziona questo elemento in una scatola con bordo |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Posiziona questo elemento in una scatola non visuale (raggruppamento logico) che viene usata per raggruppare componenti di un'equazione o altra istanza di testo matematico. Un oggetto racchiuso può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Posiziona gli elementi figlio in un array verticale |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Imposta una barra nella parte inferiore di questo elemento |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Salva il contenuto di questo [`MathBlock`](../mathblock) come MathML |

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