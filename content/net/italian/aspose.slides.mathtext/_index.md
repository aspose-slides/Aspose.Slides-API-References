---
title: Aspose.Slides.MathText
second_title: Riferimento API Aspose.Sildes per .NET
description: Contiene classi per lavorare con testo matematico nelle presentazioni Microsoft PowerPoint.
type: docs
weight: 140
url: /it/aspose.slides.mathtext/
---
Contiene classi per lavorare con testo matematico nelle presentazioni Microsoft PowerPoint.

## Classi

| Classe | Descrizione |
| --- | --- |
| [BaseScript](./basescript) | Script matematico |
| [MathAccent](./mathaccent) | Specifica la funzione di accento, costituita da una base e un segno diacritico combinante. Esempio: 𝑎́ |
| [MathAccentFactory](./mathaccentfactory) | Consente di creare un accento matematico |
| [MathArray](./matharray) | Specifica un array verticale di equazioni o di qualsiasi oggetto matematico |
| [MathArrayFactory](./matharrayfactory) | Consente di creare un array matematico |
| [MathBar](./mathbar) | Specifica la funzione barra, costituita da un argomento di base e da una barra superiore o inferiore |
| [MathBarFactory](./mathbarfactory) | Consente di creare una barra matematica |
| [MathBlock](./mathblock) | Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria linea. Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da math block. |
| [MathBlockFactory](./mathblockfactory) | Consente di creare un math block |
| [MathBorderBox](./mathborderbox) | Disegna un rettangolo o altro bordo attorno a IMathElement. |
| [MathBorderBoxFactory](./mathborderboxfactory) | Consente di creare una math border box |
| [MathBox](./mathbox) | Specifica l'incapsulamento logico (packaging) di un elemento matematico. Per esempio, un oggetto incapsulato può fungere da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. Per esempio, l'operatore "==" dovrebbe essere incapsulato per prevenire interruzioni di riga. |
| [MathBoxFactory](./mathboxfactory) | Consente di creare una math box |
| [MathDelimiter](./mathdelimiter) | Specifica l'oggetto delimitatore, costituito da caratteri di apertura e chiusura (come parentesi tonde, graffe, quadre e barre verticali) e da uno o più elementi matematici all'interno, separati da un carattere specificato. Esempi: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [MathDelimiterFactory](./mathdelimiterfactory) | Consente di creare un delimitatore matematico |
| [MathElementBase](./mathelementbase) | Classe base per IMathElement con l'implementazione di alcuni metodi comuni a tutte le classi ereditate. Solo per uso interno. La classe ereditata deve essere IMathElement. |
| [MathematicalText](./mathematicaltext) | Testo matematico |
| [MathematicalTextFactory](./mathematicaltextfactory) | Consente di creare un elemento MathematicalText |
| [MathFraction](./mathfraction) | Specifica l'oggetto frazione, costituito da un numeratore e un denominatore separati da una barra di frazione. La barra di frazione può essere orizzontale o diagonale, a seconda delle proprietà della frazione. L'oggetto frazione è anche usato per rappresentare la funzione stack, che posiziona un elemento sopra un altro, senza barra di frazione. |
| [MathFractionFactory](./mathfractionfactory) | Consente di creare una frazione matematica |
| [MathFunction](./mathfunction) | Specifica una funzione di un argomento. |
| [MathFunctionFactory](./mathfunctionfactory) | Consente di creare una funzione matematica |
| [MathGroupingCharacter](./mathgroupingcharacter) | Specifica un simbolo di raggruppamento sopra o sotto un'espressione, solitamente per evidenziare la relazione tra gli elementi |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory) | Consente di creare un carattere di raggruppamento matematico |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement) | Specifica l'oggetto Sub-Superscript, costituito da una base e un pedice e apice posizionati a sinistra della base. |
| [MathLimit](./mathlimit) | Specifica l'oggetto Limit, costituito da testo sulla linea di base e testo di dimensione ridotta immediatamente sopra o sotto di esso. |
| [MathLimitFactory](./mathlimitfactory) | Consente di creare IMathLimit |
| [MathMatrix](./mathmatrix) | Specifica l'oggetto Matrix, costituito da elementi figli disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per inserire la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore (IMathDelimiter). Gli argomenti null possono essere usati per creare spazi vuoti nelle matrici. |
| [MathMatrixFactory](./mathmatrixfactory) | Consente di creare una matrice matematica |
| [MathNaryOperator](./mathnaryoperator) | Specifica un oggetto matematico N-ario, come Somma e Integrale. È costituito da un operatore, una base (o operando) e limiti superiori e inferiori opzionali. Esempi di operatori N-ari sono: Somma, Unione, Intersezione, Integrale. |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory) | Consente di creare IMathNaryOperator |
| [MathParagraph](./mathparagraph) | Paragrafo matematico che è un contenitore per blocchi matematici (IMathBlock) |
| [MathParagraphFactory](./mathparagraphfactory) | Consente di creare un paragrafo matematico |
| [MathPhantom](./mathphantom) | Rappresenta un oggetto phantom math (&lt;m:phant&gt;) che influisce sul layout del suo elemento figlio senza necessariamente visualizzarlo. Un phantom può nascondere la sua espressione di base preservandone larghezza, altezza o profondità per allineare le formule o riservare spazio. La visibilità e il comportamento geometrico sono controllati da proprietà come Show, ZeroWid, ZeroAsc, ZeroDesc e Transp. |
| [MathPortion](./mathportion) | Rappresenta una porzione con contesto matematico al suo interno. |
| [MathRadical](./mathradical) | Specifica la funzione radice, costituita da una base e un grado opzionale. Esempio di oggetto radice è √𝑥. |
| [MathRadicalFactory](./mathradicalfactory) | Consente di creare una radice matematica |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement) | Specifica l'oggetto Sub-Superscript, costituito da una base e un pedice e apice posizionati a destra della base. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory) | Consente di creare IMathRightSubSuperscriptElementFactory |
| [MathSubscriptElement](./mathsubscriptelement) | Specifica l'oggetto subscript, costituito da una base e un subscript di dimensione ridotta posizionato sotto e a destra. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory) | Consente di creare IMathSubscriptElement |
| [MathSuperscriptElement](./mathsuperscriptelement) | Specifica l'oggetto superscript, costituito da una base e un superscript di dimensione ridotta posizionato sopra e a destra |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory) | Consente di creare IMathSuperscriptElement |

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IMathAccent](./imathaccent) | Specifica la funzione di accento, costituita da una base e un segno diacritico combinante. Esempio: 𝑎́ |
| [IMathAccentFactory](./imathaccentfactory) | Consente di creare un accento matematico |
| [IMathArray](./imatharray) | Specifica un array verticale di equazioni o di qualsiasi oggetto matematico |
| [IMathArrayFactory](./imatharrayfactory) | Consente di creare un array matematico |
| [IMathBar](./imathbar) | Specifica la funzione barra, costituita da un argomento di base e da una barra superiore o inferiore |
| [IMathBarFactory](./imathbarfactory) | Consente di creare una barra matematica |
| [IMathBlock](./imathblock) | Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria linea. Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da math block. |
| [IMathBlockCollection](./imathblockcollection) | Raccolta di blocchi matematici (IMathBlock) |
| [IMathBlockFactory](./imathblockfactory) | Consente di creare un math block |
| [IMathBorderBox](./imathborderbox) | Disegna un rettangolo o altro bordo attorno a IMathElement. |
| [IMathBorderBoxFactory](./imathborderboxfactory) | Consente di creare una math border box |
| [IMathBox](./imathbox) | Specifica l'incapsulamento logico (packaging) di un elemento matematico. Per esempio, un oggetto incapsulato può fungere da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga al suo interno. Per esempio, l'operatore "==" dovrebbe essere incapsulato per prevenire interruzioni di riga. |
| [IMathBoxFactory](./imathboxfactory) | Consente di creare una math box |
| [IMathDelimiter](./imathdelimiter) | Specifica l'oggetto delimitatore, costituito da caratteri di apertura e chiusura (come parentesi tonde, graffe, quadre e barre verticali) e da uno o più elementi matematici all'interno, separati da un carattere specificato. Esempi: (𝑥2); [𝑥2&#x7C;𝑦2] |
| [IMathDelimiterFactory](./imathdelimiterfactory) | Consente di creare un delimitatore matematico |
| [IMathElement](./imathelement) | Interfaccia base di qualsiasi elemento matematico: frazione, testo matematico, funzione, espressione con più elementi ecc. |
| [IMathElementCollection](./imathelementcollection) | Rappresenta una raccolta di elementi matematici (MathElement). |
| [IMathematicalText](./imathematicaltext) | Testo matematico |
| [IMathematicalTextFactory](./imathematicaltextfactory) | Consente di creare un elemento MathematicalText |
| [IMathFraction](./imathfraction) | Specifica l'oggetto frazione, costituito da un numeratore e un denominatore separati da una barra di frazione. La barra di frazione può essere orizzontale o diagonale, a seconda delle proprietà della frazione. L'oggetto frazione è anche usato per rappresentare la funzione stack, che posiziona un elemento sopra un altro, senza barra di frazione. |
| [IMathFractionFactory](./imathfractionfactory) | Consente di creare una frazione matematica |
| [IMathFunction](./imathfunction) | Specifica una funzione di un argomento. |
| [IMathFunctionFactory](./imathfunctionfactory) | Consente di creare una funzione matematica |
| [IMathGroupingCharacter](./imathgroupingcharacter) | Specifica un simbolo di raggruppamento sopra o sotto un'espressione, solitamente per evidenziare la relazione tra gli elementi |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory) | Consente di creare un carattere di raggruppamento matematico |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement) | Specifica l'oggetto Sub-Superscript, costituito da una base e un pedice e apice posizionati a sinistra della base. |
| [IMathLimit](./imathlimit) | Specifica l'oggetto Limit, costituito da testo sulla linea di base e testo di dimensione ridotta immediatamente sopra o sotto di esso. |
| [IMathLimitFactory](./imathlimitfactory) | Consente di creare IMathLimit |
| [IMathMatrix](./imathmatrix) | Specifica l'oggetto Matrix, costituito da elementi figli disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per inserire la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore (IMathDelimiter). Gli argomenti null possono essere usati per creare spazi vuoti nelle matrici. |
| [IMathMatrixFactory](./imathmatrixfactory) | Consente di creare una matrice matematica |
| [IMathNaryOperator](./imathnaryoperator) | Specifica un oggetto matematico N-ario, come Somma e Integrale. È costituito da un operatore, una base (o operando) e limiti superiori e inferiori opzionali. Esempi di operatori N-ari sono: Somma, Unione, Intersezione, Integrale. |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory) | Consente di creare IMathNaryOperator |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties) | Specifica le proprietà di IMathNaryOperator |
| [IMathParagraph](./imathparagraph) | Paragrafo matematico che è un contenitore per blocchi matematici (IMathBlock) |
| [IMathParagraphFactory](./imathparagraphfactory) | Consente di creare un paragrafo matematico |
| [IMathPhantom](./imathphantom) | Rappresenta un oggetto phantom math (&lt;m:phant&gt;) che influisce sul layout del suo elemento figlio senza necessariamente visualizzarlo. Un phantom può nascondere la sua espressione di base preservandone larghezza, altezza o profondità per allineare le formule o riservare spazio. La visibilità e il comportamento geometrico sono controllati da proprietà come Show, ZeroWid, ZeroAsc, ZeroDesc e Transp. |
| [IMathPortion](./imathportion) | Rappresenta una porzione con contesto matematico al suo interno. |
| [IMathRadical](./imathradical) | Specifica la funzione radice, costituita da una base e un grado opzionale. Esempio di oggetto radice è √𝑥. |
| [IMathRadicalFactory](./imathradicalfactory) | Consente di creare una radice matematica |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement) | Specifica l'oggetto Sub-Superscript, costituito da una base e un pedice e apice posizionati a destra della base. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory) | Consente di creare IMathRightSubSuperscriptElementFactory |
| [IMathSubscriptElement](./imathsubscriptelement) | Specifica l'oggetto subscript, costituito da una base e un subscript di dimensione ridotta posizionato sotto e a destra. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory) | Consente di creare IMathSubscriptElement |
| [IMathSuperscriptElement](./imathsuperscriptelement) | Specifica l'oggetto superscript, costituito da una base e un superscript di dimensione ridotta posizionato sopra e a destra |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory) | Consente di creare IMathSuperscriptElement |

## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape) | La posizione e la dimensione dei delimitatori rispetto al contenuto degli operandi |
| [MathFractionTypes](./mathfractiontypes) | Tipi di frazione |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument) | Funzioni matematiche comuni di un argomento |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments) | Funzioni matematiche comuni di due argomenti |
| [MathHorizontalAlignment](./mathhorizontalalignment) | Allineamento orizzontale |
| [MathIntegralTypes](./mathintegraltypes) | Tipi di integrali matematici |
| [MathJustification](./mathjustification) | Specifica la giustificazione del paragrafo matematico (una serie di istanze adiacenti di testo matematico all'interno dello stesso paragrafo) |
| [MathLimitLocations](./mathlimitlocations) | Posizione dei limiti (subscript/superscript) negli operatori n-ari. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes) | Tipi di operatore n-ario IMathNaryOperator (esclusi gli integrali) Per gli integrali [`MathIntegralTypes`](../aspose.slides.mathtext/mathintegraltypes) |
| [MathRowSpacingRule](./mathrowspacingrule) | Il tipo di spaziatura verticale tra le colonne in una matrice o array |
| [MathSpacingRules](./mathspacingrules) | Tipi di intervallo (spaziatura orizzontale) tra le colonne di una matrice |
| [MathTopBotPositions](./mathtopbotpositions) | Enumerazione delle posizioni superiore/inferiore |
| [MathVerticalAlignment](./mathverticalalignment) | Allineamento verticale |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->