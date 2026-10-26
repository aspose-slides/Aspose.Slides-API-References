---
title: aspose.slides.mathtext
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/
---
Contiene classi per lavorare con testo matematico nelle presentazioni Microsoft PowerPoint.
## Classi

| Classe | Descrizione |
| :- | :- |
| [`BaseScript`](/slides/python-net/it/aspose.slides.mathtext/basescript/) | Script matematico |
| [`IMathAccent`](/slides/python-net/it/aspose.slides.mathtext/imathaccent/) | Specifica la funzione di accento, costituita da una base e un segno diacritico combinante<br/>            Esempio: 𝑎́ |
| [`IMathAccentFactory`](/slides/python-net/it/aspose.slides.mathtext/imathaccentfactory/) | Consente di creare un accento matematico |
| [`IMathArray`](/slides/python-net/it/aspose.slides.mathtext/imatharray/) | Specifica un array verticale di equazioni o di qualsiasi oggetto matematico |
| [`IMathArrayFactory`](/slides/python-net/it/aspose.slides.mathtext/imatharrayfactory/) | Consente di creare un array matematico |
| [`IMathBar`](/slides/python-net/it/aspose.slides.mathtext/imathbar/) | Specifica la funzione bar, costituita da un argomento di base e da una barra superiore o inferiore |
| [`IMathBarFactory`](/slides/python-net/it/aspose.slides.mathtext/imathbarfactory/) | Consente di creare una barra matematica |
| [`IMathBlock`](/slides/python-net/it/aspose.slides.mathtext/imathblock/) | Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria riga.<br/>            Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da un blocco matematico. |
| [`IMathBlockCollection`](/slides/python-net/it/aspose.slides.mathtext/imathblockcollection/) | Raccolta di blocchi matematici (IMathBlock) |
| [`IMathBlockFactory`](/slides/python-net/it/aspose.slides.mathtext/imathblockfactory/) | Consente di creare un blocco matematico |
| [`IMathBorderBox`](/slides/python-net/it/aspose.slides.mathtext/imathborderbox/) | Disegna un bordo rettangolare o di altro tipo attorno al IMathElement. |
| [`IMathBorderBoxFactory`](/slides/python-net/it/aspose.slides.mathtext/imathborderboxfactory/) | Consente di creare una casella di bordo matematico |
| [`IMathBox`](/slides/python-net/it/aspose.slides.mathtext/imathbox/) | Specifica l'incapsulamento logico (packaging) dell'elemento matematico.<br/>            Ad esempio, un oggetto incapsulato può fungere da emulatore di operatore con o senza un punto di allineamento, <br/>            fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno.<br/>            Ad esempio, l'operatore "==" dovrebbe essere incapsulato per impedire interruzioni di riga. |
| [`IMathBoxFactory`](/slides/python-net/it/aspose.slides.mathtext/imathboxfactory/) | Consente di creare una casella matematica |
| [`IMathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiter/) | Specifica l'oggetto delimitatore, costituito da caratteri di apertura e chiusura (come parentesi, <br/>            parentesi graffe, parentesi quadre e barre verticali), e da uno o più elementi matematici all'interno, separati da un carattere specificato.<br/>            Esempi: (𝑥2); [𝑥2\|𝑦2] |
| [`IMathDelimiterFactory`](/slides/python-net/it/aspose.slides.mathtext/imathdelimiterfactory/) | Consente di creare un delimitatore matematico |
| [`IMathElement`](/slides/python-net/it/aspose.slides.mathtext/imathelement/) | Interfaccia di base di qualsiasi elemento matematico: <br/>            frazione, testo matematico, funzione, espressione con più elementi ecc. |
| [`IMathElementCollection`](/slides/python-net/it/aspose.slides.mathtext/imathelementcollection/) | Rappresenta una raccolta di elementi matematici (MathElement). |
| [`IMathFraction`](/slides/python-net/it/aspose.slides.mathtext/imathfraction/) | Specifica l'oggetto frazione, costituito da un numeratore e un denominatore separati da una barra di frazione.<br/>            La barra di frazione può essere orizzontale o diagonale, a seconda delle proprietà della frazione.<br/>            L'oggetto frazione è anche usato per rappresentare la funzione stack, che colloca un elemento sopra un altro, senza barra di frazione. |
| [`IMathFractionFactory`](/slides/python-net/it/aspose.slides.mathtext/imathfractionfactory/) | Consente di creare una frazione matematica |
| [`IMathFunction`](/slides/python-net/it/aspose.slides.mathtext/imathfunction/) | Specifica una funzione di un argomento. |
| [`IMathFunctionFactory`](/slides/python-net/it/aspose.slides.mathtext/imathfunctionfactory/) | Consente di creare una funzione matematica |
| [`IMathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/imathgroupingcharacter/) | Specifica un simbolo di raggruppamento sopra o sotto un'espressione, di solito per evidenziare la relazione tra gli elementi |
| [`IMathGroupingCharacterFactory`](/slides/python-net/it/aspose.slides.mathtext/imathgroupingcharacterfactory/) | Consente di creare un carattere di raggruppamento matematico |
| [`IMathLeftSubSuperscriptElement`](/slides/python-net/it/aspose.slides.mathtext/imathleftsubsuperscriptelement/) | Specifica l'oggetto Sub-Superscript, che consiste in una base <br/>            e un subscript e superscript posizionati a sinistra della base. |
| [`IMathLimit`](/slides/python-net/it/aspose.slides.mathtext/imathlimit/) | Specifica l'oggetto Limit, costituito da testo sulla linea di base e testo di dimensione ridotta immediatamente sopra o sotto di esso. |
| [`IMathLimitFactory`](/slides/python-net/it/aspose.slides.mathtext/imathlimitfactory/) | Consente di creare IMathLimit |
| [`IMathMatrix`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/) | Specifica l'oggetto Matrix, costituito da elementi figli disposti in una o più righe e colonne.<br/>            È importante notare che le matrici non hanno delimitatori integrati.<br/>            Per inserire la matrice tra parentesi è necessario usare l'oggetto delimitatore (IMathDelimiter).<br/>            Argomenti nulli possono essere usati per creare spazi vuoti nelle matrici. |
| [`IMathMatrixFactory`](/slides/python-net/it/aspose.slides.mathtext/imathmatrixfactory/) | Consente di creare una matrice matematica |
| [`IMathNaryOperator`](/slides/python-net/it/aspose.slides.mathtext/imathnaryoperator/) | Specifica un oggetto matematico N-ario, come Somma e Integrale.<br/>            Consiste in un operatore, una base (o operando), e limiti superiori e inferiori opzionali. <br/>            Esempi di operatori N-ari sono: Somma, Unione, Intersezione, Integrale |
| [`IMathNaryOperatorFactory`](/slides/python-net/it/aspose.slides.mathtext/imathnaryoperatorfactory/) | Consente di creare IMathNaryOperator |
| [`IMathNaryOperatorProperties`](/slides/python-net/it/aspose.slides.mathtext/imathnaryoperatorproperties/) | Specifica le proprietà di IMathNaryOperator |
| [`IMathParagraph`](/slides/python-net/it/aspose.slides.mathtext/imathparagraph/) | Paragrafo matematico che è un contenitore per blocchi matematici (IMathBlock) |
| [`IMathParagraphFactory`](/slides/python-net/it/aspose.slides.mathtext/imathparagraphfactory/) | Consente di creare un paragrafo matematico |
| [`IMathPhantom`](/slides/python-net/it/aspose.slides.mathtext/imathphantom/) | Rappresenta un oggetto fantasma matematico (<m:phant>) che influisce sul layout del suo elemento figlio<br/>            senza necessariamente visualizzarlo. Un fantasma può nascondere la sua espressione di base preservando<br/>            la sua larghezza, altezza o profondità per allineare formule o riservare spazio. <br/>            La visibilità e il comportamento geometrico sono controllati da proprietà quali Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc e Transp. |
| [`IMathPortion`](/slides/python-net/it/aspose.slides.mathtext/imathportion/) | Rappresenta una porzione con contesto matematico al suo interno. |
| [`IMathRadical`](/slides/python-net/it/aspose.slides.mathtext/imathradical/) | Specifica la funzione radice, costituita da una base e da un grado opzionale.<br/>            Esempio di oggetto radice è √𝑥. |
| [`IMathRadicalFactory`](/slides/python-net/it/aspose.slides.mathtext/imathradicalfactory/) | Consente di creare una radice matematica |
| [`IMathRightSubSuperscriptElement`](/slides/python-net/it/aspose.slides.mathtext/imathrightsubsuperscriptelement/) | Specifica l'oggetto Sub-Superscript, che consiste in una base <br/>            e un subscript e superscript posizionati a destra della base. |
| [`IMathRightSubSuperscriptElementFactory`](/slides/python-net/it/aspose.slides.mathtext/imathrightsubsuperscriptelementfactory/) | Consente di creare IMathRightSubSuperscriptElementFactory |
| [`IMathSubscriptElement`](/slides/python-net/it/aspose.slides.mathtext/imathsubscriptelement/) | Specifica l'oggetto subscript, che consiste in una base <br/>            e un subscript di dimensione ridotta posizionato sotto e a destra. |
| [`IMathSubscriptElementFactory`](/slides/python-net/it/aspose.slides.mathtext/imathsubscriptelementfactory/) | Consente di creare IMathSubscriptElement |
| [`IMathSuperscriptElement`](/slides/python-net/it/aspose.slides.mathtext/imathsuperscriptelement/) | Specifica l'oggetto superscript, che consiste in una base <br/>            e un superscript di dimensione ridotta posizionato sopra e a destra |
| [`IMathSuperscriptElementFactory`](/slides/python-net/it/aspose.slides.mathtext/imathsuperscriptelementfactory/) | Consente di creare IMathSuperscriptElement |
| [`IMathematicalText`](/slides/python-net/it/aspose.slides.mathtext/imathematicaltext/) | Testo matematico |
| [`IMathematicalTextFactory`](/slides/python-net/it/aspose.slides.mathtext/imathematicaltextfactory/) | Consente di creare un elemento MathematicalText |
| [`MathAccent`](/slides/python-net/it/aspose.slides.mathtext/mathaccent/) | Specifica la funzione di accento, costituita da una base e un segno diacritico combinante<br/>            Esempio: 𝑎́ |
| [`MathAccentFactory`](/slides/python-net/it/aspose.slides.mathtext/mathaccentfactory/) | Consente di creare un accento matematico |
| [`MathArray`](/slides/python-net/it/aspose.slides.mathtext/matharray/) | Specifica un array verticale di equazioni o di qualsiasi oggetto matematico |
| [`MathArrayFactory`](/slides/python-net/it/aspose.slides.mathtext/matharrayfactory/) | Consente di creare un array matematico |
| [`MathBar`](/slides/python-net/it/aspose.slides.mathtext/mathbar/) | Specifica la funzione bar, costituita da un argomento di base e da una barra superiore o inferiore |
| [`MathBarFactory`](/slides/python-net/it/aspose.slides.mathtext/mathbarfactory/) | Consente di creare una barra matematica |
| [`MathBlock`](/slides/python-net/it/aspose.slides.mathtext/mathblock/) | Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria riga.<br/>            Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da un blocco matematico. |
| [`MathBlockFactory`](/slides/python-net/it/aspose.slides.mathtext/mathblockfactory/) | Consente di creare un blocco matematico |
| [`MathBorderBox`](/slides/python-net/it/aspose.slides.mathtext/mathborderbox/) | Disegna un bordo rettangolare o di altro tipo attorno al IMathElement. |
| [`MathBorderBoxFactory`](/slides/python-net/it/aspose.slides.mathtext/mathborderboxfactory/) | Consente di creare una casella di bordo matematico |
| [`MathBox`](/slides/python-net/it/aspose.slides.mathtext/mathbox/) | Specifica l'incapsulamento logico (packaging) dell'elemento matematico.<br/>            Ad esempio, un oggetto incapsulato può fungere da emulatore di operatore con o senza un punto di allineamento, <br/>            fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno.<br/>            Ad esempio, l'operatore "==" dovrebbe essere incapsulato per impedire interruzioni di riga. |
| [`MathBoxFactory`](/slides/python-net/it/aspose.slides.mathtext/mathboxfactory/) | Consente di creare una casella matematica |
| [`MathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter/) | Specifica l'oggetto delimitatore, costituito da caratteri di apertura e chiusura (come parentesi, <br/>            parentesi graffe, parentesi quadre e barre verticali), e da uno o più elementi matematici all'interno, separati da un carattere specificato.<br/>            Esempi: (𝑥2); [𝑥2\|𝑦2] |
| [`MathDelimiterFactory`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiterfactory/) | Consente di creare un delimitatore matematico |
| [`MathElementBase`](/slides/python-net/it/aspose.slides.mathtext/mathelementbase/) | Classe base per IMathElement con l'implementazione di alcuni metodi comuni a tutte le classi ereditate<br/>            Solo per uso interno. La classe ereditata deve essere IMathElement. |
| [`MathFraction`](/slides/python-net/it/aspose.slides.mathtext/mathfraction/) | Specifica l'oggetto frazione, costituito da un numeratore e un denominatore separati da una barra di frazione.<br/>            La barra di frazione può essere orizzontale o diagonale, a seconda delle proprietà della frazione.<br/>            L'oggetto frazione è anche usato per rappresentare la funzione stack, che colloca un elemento sopra un altro, senza barra di frazione. |
| [`MathFractionFactory`](/slides/python-net/it/aspose.slides.mathtext/mathfractionfactory/) | Consente di creare una frazione matematica |
| [`MathFunction`](/slides/python-net/it/aspose.slides.mathtext/mathfunction/) | Specifica una funzione di un argomento. |
| [`MathFunctionFactory`](/slides/python-net/it/aspose.slides.mathtext/mathfunctionfactory/) | Consente di creare una funzione matematica |
| [`MathGroupingCharacter`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacter/) | Specifica un simbolo di raggruppamento sopra o sotto un'espressione, di solito per evidenziare la relazione tra gli elementi |
| [`MathGroupingCharacterFactory`](/slides/python-net/it/aspose.slides.mathtext/mathgroupingcharacterfactory/) | Consente di creare un carattere di raggruppamento matematico |
| [`MathLeftSubSuperscriptElement`](/slides/python-net/it/aspose.slides.mathtext/mathleftsubsuperscriptelement/) | Specifica l'oggetto Sub-Superscript, che consiste in una base <br/>            e un subscript e superscript posizionati a sinistra della base. |
| [`MathLimit`](/slides/python-net/it/aspose.slides.mathtext/mathlimit/) | Specifica l'oggetto Limit, costituito da testo sulla linea di base e testo di dimensione ridotta immediatamente sopra o sotto di esso. |
| [`MathLimitFactory`](/slides/python-net/it/aspose.slides.mathtext/mathlimitfactory/) | Consente di creare IMathLimit |
| [`MathMatrix`](/slides/python-net/it/aspose.slides.mathtext/mathmatrix/) | Specifica l'oggetto Matrix, costituito da elementi figli disposti in una o più righe e colonne.<br/>            È importante notare che le matrici non hanno delimitatori integrati.<br/>            Per inserire la matrice tra parentesi è necessario usare l'oggetto delimitatore (IMathDelimiter).<br/>            Argomenti nulli possono essere usati per creare spazi vuoti nelle matrici. |
| [`MathMatrixFactory`](/slides/python-net/it/aspose.slides.mathtext/mathmatrixfactory/) | Consente di creare una matrice matematica |
| [`MathNaryOperator`](/slides/python-net/it/aspose.slides.mathtext/mathnaryoperator/) | Specifica un oggetto matematico N-ario, come Somma e Integrale.<br/>            Consiste in un operatore, una base (o operando), e limiti superiori e inferiori opzionali. <br/>            Esempi di operatori N-ari sono: Somma, Unione, Intersezione, Integrale |
| [`MathNaryOperatorFactory`](/slides/python-net/it/aspose.slides.mathtext/mathnaryoperatorfactory/) | Consente di creare IMathNaryOperator |
| [`MathParagraph`](/slides/python-net/it/aspose.slides.mathtext/mathparagraph/) | Paragrafo matematico che è un contenitore per blocchi matematici (IMathBlock) |
| [`MathParagraphFactory`](/slides/python-net/it/aspose.slides.mathtext/mathparagraphfactory/) | Consente di creare un paragrafo matematico |
| [`MathPhantom`](/slides/python-net/it/aspose.slides.mathtext/mathphantom/) | Rappresenta un oggetto fantasma matematico (<m:phant>) che influisce sul layout del suo elemento figlio<br/>            senza necessariamente visualizzarlo. Un fantasma può nascondere la sua espressione di base preservando<br/>            la sua larghezza, altezza o profondità per allineare formule o riservare spazio. <br/>            La visibilità e il comportamento geometrico sono controllati da proprietà quali Show, ZeroWid, ZeroAsc, <br/>            ZeroDesc e Transp. |
| [`MathPortion`](/slides/python-net/it/aspose.slides.mathtext/mathportion/) | Rappresenta una porzione con contesto matematico al suo interno. |
| [`MathRadical`](/slides/python-net/it/aspose.slides.mathtext/mathradical/) | Specifica la funzione radice, costituita da una base e da un grado opzionale.<br/>            Esempio di oggetto radice è √𝑥. |
| [`MathRadicalFactory`](/slides/python-net/it/aspose.slides.mathtext/mathradicalfactory/) | Consente di creare una radice matematica |
| [`MathRightSubSuperscriptElement`](/slides/python-net/it/aspose.slides.mathtext/mathrightsubsuperscriptelement/) | Specifica l'oggetto Sub-Superscript, che consiste in una base <br/>            e un subscript e superscript posizionati a destra della base. |
| [`MathRightSubSuperscriptElementFactory`](/slides/python-net/it/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/) | Consente di creare IMathRightSubSuperscriptElementFactory |
| [`MathSubscriptElement`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelement/) | Specifica l'oggetto subscript, che consiste in una base <br/>            e un subscript di dimensione ridotta posizionato sotto e a destra. |
| [`MathSubscriptElementFactory`](/slides/python-net/it/aspose.slides.mathtext/mathsubscriptelementfactory/) | Consente di creare IMathSubscriptElement |
| [`MathSuperscriptElement`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelement/) | Specifica l'oggetto superscript, che consiste in una base <br/>            e un superscript di dimensione ridotta posizionato sopra e a destra |
| [`MathSuperscriptElementFactory`](/slides/python-net/it/aspose.slides.mathtext/mathsuperscriptelementfactory/) | Consente di creare IMathSuperscriptElement |
| [`MathematicalText`](/slides/python-net/it/aspose.slides.mathtext/mathematicaltext/) | Testo matematico |
| [`MathematicalTextFactory`](/slides/python-net/it/aspose.slides.mathtext/mathematicaltextfactory/) | Consente di creare un elemento MathematicalText |

## Enumerazioni

| Enumerazione | Descrizione |
| :- | :- |
| [`MathDelimiterShape`](/slides/python-net/it/aspose.slides.mathtext/mathdelimitershape/) | La posizione e la dimensione dei delimitatori rispetto al contenuto degli operandi |
| [`MathFractionTypes`](/slides/python-net/it/aspose.slides.mathtext/mathfractiontypes/) | Tipi di frazione |
| [`MathFunctionsOfOneArgument`](/slides/python-net/it/aspose.slides.mathtext/mathfunctionsofoneargument/) | Funzioni matematiche comuni di un argomento |
| [`MathFunctionsOfTwoArguments`](/slides/python-net/it/aspose.slides.mathtext/mathfunctionsoftwoarguments/) | Funzioni matematiche comuni di due argomenti |
| [`MathHorizontalAlignment`](/slides/python-net/it/aspose.slides.mathtext/mathhorizontalalignment/) | Allineamento orizzontale |
| [`MathIntegralTypes`](/slides/python-net/it/aspose.slides.mathtext/mathintegraltypes/) | Tipi di integrali matematici |
| [`MathJustification`](/slides/python-net/it/aspose.slides.mathtext/mathjustification/) | Specifica la giustificazione del paragrafo matematico (una serie di istanze adiacenti di testo matematico all'interno dello stesso paragrafo) |
| [`MathLimitLocations`](/slides/python-net/it/aspose.slides.mathtext/mathlimitlocations/) | Posizione dei limiti (subscript/superscript) negli operatori n-ari. |
| [`MathNaryOperatorTypes`](/slides/python-net/it/aspose.slides.mathtext/mathnaryoperatortypes/) | Tipi di operatore n-ario IMathNaryOperator (esclusi gli integrali)<br/>            Per gli integrali [`MathIntegralTypes`](/slides/python-net/it/aspose.slides.mathtext/mathintegraltypes) |
| [`MathRowSpacingRule`](/slides/python-net/it/aspose.slides.mathtext/mathrowspacingrule/) | Il tipo di spaziatura verticale tra colonne in una matrice o array |
| [`MathSpacingRules`](/slides/python-net/it/aspose.slides.mathtext/mathspacingrules/) | Tipi di spazio (spaziatura orizzontale) tra colonne di una matrice |
| [`MathTopBotPositions`](/slides/python-net/it/aspose.slides.mathtext/mathtopbotpositions/) | Enumerazione delle posizioni superiore/inferiore |
| [`MathVerticalAlignment`](/slides/python-net/it/aspose.slides.mathtext/mathverticalalignment/) | Allineamento verticale |