---
title: MathMatrix
second_title: Riferimento API Aspose.Sildes per .NET
description: Specifica l'oggetto Matrix composto da elementi figlio disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per inserire la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore IMathDelimiter. È possibile utilizzare argomenti null per creare spazi vuoti nelle matrici.
type: docs
weight: 8830
url: /it/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix classe

Specifica l'oggetto Matrix, composto da elementi figlio disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per inserire la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore (IMathDelimiter). È possibile utilizzare argomenti null per creare spazi vuoti nelle matrici.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | Inizializza una nuova istanza della classe MathMatrix. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Specifica l'allineamento verticale rispetto al testo circostante. I valori possibili sono top, bottom e center. Predefinito: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Numero di colonne nella matrice |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Il valore della spaziatura orizzontale tra le colonne di una matrice; se ColumnGapRule è impostato a 3 ("Exactly"), l'unità è interpretata come twip (1/20 di punto). Se ColumnGapRule è impostato a 4 ("Multiple"), l'unità è interpretata come numero di incrementi di 0,5 em. Negli altri casi è ignorata. Predefinito: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Il tipo di spaziatura orizzontale tra le colonne di una matrice; le unità di spaziatura orizzontale possono essere em o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Nasconde i segnaposto per gli elementi vuoti della matrice. Predefinito: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Elemento della matrice |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Larghezza minima della colonna in twip (1/20 di punto). La spaziatura del divario (nota anche come "Column Gap" o "Gap Width") viene aggiunta a MinColumnWidth per determinare la spaziatura totale delle colonne della matrice (distanza tra gli stessi bordi di colonne diverse). Predefinito: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Numero di righe nella matrice |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Il valore della spaziatura verticale tra le righe di una matrice; se RowGapRule è impostato a 3 ("Exactly"), l'unità è interpretata come twip (1/20 di punto). Se RowGapRule è impostato a 4 ("Multiple"), l'unità è interpretata come mezze linee. Predefinito: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Il tipo di spaziatura verticale tra le righe di una matrice; le unità di spaziatura verticale possono essere linee o punti (memorizzati come twip). Predefinito: SingleSpacingGap (0) |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Imposta un segno di accento (un carattere sopra questo elemento) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Esegue la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Esegue la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Esegue la funzione specificata usando questa istanza come argomento |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Esegue la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Esegue la funzione specificata usando questa istanza come argomento e l'argomento aggiuntivo specificato |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Elimina la colonna specificata |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Elimina la riga specificata |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Crea una frazione con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Crea una frazione del tipo specificato con questo numeratore e il denominatore specificato |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Racchiude un elemento matematico tra parentesi |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Racchiude un elemento matematico nei caratteri specificati, come parentesi o altri caratteri di inquadratura |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Esegue una funzione di un argomento usando questa istanza come nome della funzione |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Esegue una funzione di un argomento usando questa istanza come nome della funzione |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Ottiene gli elementi figli |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Ottiene l'allineamento orizzontale della colonna specificata |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Colloca questo elemento in un gruppo usando una parentesi graffa inferiore |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Colloca questo elemento in un gruppo usando un carattere di raggruppamento come una parentesi graffa inferiore o altro |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Inserisce una nuova colonna dopo quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Inserisce una nuova colonna prima di quella specificata. Inizialmente tutti gli elementi nella nuova colonna sono null. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Inserisce una nuova riga dopo quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Inserisce una nuova riga prima di quella specificata. Inizialmente tutti gli elementi nella nuova riga sono null. |
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
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Imposta l'allineamento orizzontale della colonna specificata |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Imposta l'allineamento orizzontale delle colonne specificate |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Esegue il limite inferiore |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Esegue il limite inferiore |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Crea pedice |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Crea pedice |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Crea pedice e apice a sinistra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Crea pedice e apice a destra |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Crea pedice e apice a destra |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Crea apice |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Crea apice |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Esegue il limite superiore |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Esegue il limite superiore |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Colloca questo elemento in un riquadro |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Colloca questo elemento in un riquadro |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Colloca questo elemento in un box non visivo (raggruppamento logico) usato per raggruppare componenti di un'equazione o altra istanza di testo matematico. Un oggetto racchiuso può (ad esempio) fungere da emulatore di operatore con o senza punto di allineamento, servire come punto di interruzione di linea, o essere raggruppato in modo da non consentire interruzioni di linea al suo interno. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Inserisce in un array verticale |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Imposta una barra nella parte inferiore di questo elemento |

### Esempi

Esempio:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Vedi anche

* classe [MathElementBase](../mathelementbase)
* interfaccia [IMathMatrix](../imathmatrix)
* spazio dei nomi [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->