---
title: "Aspose::Slides::MathText"
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 157
url: /it/aspose.slides.mathtext/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [BaseScript](./basescript/) | Script matematico |
| [IHasControlCharacterProperties](./ihascontrolcharacterproperties/) | [IMathElement](./imathelement/) con Proprietà del Carattere [Control](../aspose.slides/control/) |
| [IMathAccent](./imathaccent/) | Specifica la funzione di accento, composta da una base e un segno diacritico combinante. Esempio: \\uD835\\uDC4E\\u0301 |
| [IMathAccentFactory](./imathaccentfactory/) | Consente di creare un accento matematico |
| [IMathArray](./imatharray/) | Specifica un array verticale di equazioni o di qualsiasi oggetto matematico |
| [IMathArrayFactory](./imatharrayfactory/) | Consente di creare un array matematico |
| [IMathBar](./imathbar/) | Specifica la funzione barra, composta da un argomento base e una barra superiore o inferiore |
| [IMathBarFactory](./imathbarfactory/) | Consente di creare una barra matematica |
| [IMathBlock](./imathblock/) | Specifica un'istanza di testo matematico contenuta all'interno di un [MathParagraph](./mathparagraph/) e che inizia su una propria riga. Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da un blocco matematico. |
| [IMathBlockCollection](./imathblockcollection/) | Raccolta di blocchi matematici ([IMathBlock](./imathblock/)) |
| [IMathBlockFactory](./imathblockfactory/) | Consente di creare un blocco matematico |
| [IMathBorderBox](./imathborderbox/) | Disegna un bordo rettangolare o di altro tipo attorno al [IMathElement](./imathelement/). |
| [IMathBorderBoxFactory](./imathborderboxfactory/) | Consente di creare una casella di bordo matematico |
| [IMathBox](./imathbox/) | Specifica l'incapsulamento logico (boxing) di un elemento matematico. Ad esempio, un oggetto incapsulato può fungere da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga all'interno. Per esempio, l'operatore \"==\" dovrebbe essere incapsulato per prevenire interruzioni di riga. |
| [IMathBoxFactory](./imathboxfactory/) | Consente di creare una casella matematica |
| [IMathDelimiter](./imathdelimiter/) | Specifica l'oggetto delimitatore, composto da caratteri di apertura e chiusura (come parentesi tonde, graffe, quadre e barre verticali) e da uno o più elementi matematici al suo interno, separati da un carattere specificato. Esempi: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [IMathDelimiterFactory](./imathdelimiterfactory/) | Consente di creare un delimitatore matematico |
| [IMathElement](./imathelement/) | Interfaccia base di qualsiasi elemento matematico: frazione, testo matematico, funzione, espressione con più elementi ecc. |
| [IMathElementCollection](./imathelementcollection/) | Rappresenta una collezione di elementi matematici (MathElement). |
| [IMathematicalText](./imathematicaltext/) | Testo matematico |
| [IMathematicalTextFactory](./imathematicaltextfactory/) | Consente di creare un elemento [MathematicalText](./mathematicaltext/) |
| [IMathFraction](./imathfraction/) | Specifica l'oggetto frazione, composto da numeratore e denominatore separati da una barra frazionaria. La barra può essere orizzontale o diagonale, a seconda delle proprietà della frazione. L'oggetto frazione è anche usato per rappresentare la funzione stack, che posiziona un elemento sopra un altro, senza barra frazionaria. |
| [IMathFractionFactory](./imathfractionfactory/) | Consente di creare una frazione matematica |
| [IMathFunction](./imathfunction/) | Specifica una funzione di un argomento. |
| [IMathFunctionFactory](./imathfunctionfactory/) | Consente di creare una funzione matematica |
| [IMathGroupingCharacter](./imathgroupingcharacter/) | Specifica un simbolo di raggruppamento sopra o sotto un'espressione, solitamente per evidenziare la relazione tra gli elementi |
| [IMathGroupingCharacterFactory](./imathgroupingcharacterfactory/) | Consente di creare un carattere di raggruppamento matematico |
| [IMathLeftSubSuperscriptElement](./imathleftsubsuperscriptelement/) | Specifica l'oggetto Sotto/Superindice, composto da una base e da un pedice e un apice posizionati a sinistra della base. |
| [IMathLimit](./imathlimit/) | Specifica l'oggetto Limite, composto da testo sulla linea di base e testo di dimensioni ridotte immediatamente sopra o sotto di esso. |
| [IMathLimitFactory](./imathlimitfactory/) | Consente di creare [IMathLimit](./imathlimit/) |
| [IMathMatrix](./imathmatrix/) | Specifica l'oggetto Matrice, composto da elementi figli disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per collocare la matrice tra parentesi è necessario usare l'oggetto delimitatore ([IMathDelimiter](./imathdelimiter/)). Gli argomenti nulli possono essere usati per creare spazi vuoti nelle matrici. |
| [IMathMatrixFactory](./imathmatrixfactory/) | Consente di creare una matrice matematica |
| [IMathNaryOperator](./imathnaryoperator/) | Specifica un oggetto matematico n-ario, come Somma e Integrale. È composto da un operatore, una base (o operando) e limiti superiori e inferiori opzionali. Esempi di operatori n-ari sono: Somma, Unione, Intersezione, Integrale |
| [IMathNaryOperatorFactory](./imathnaryoperatorfactory/) | Consente di creare [IMathNaryOperator](./imathnaryoperator/) |
| [IMathNaryOperatorProperties](./imathnaryoperatorproperties/) | Specifica le proprietà di [IMathNaryOperator](./imathnaryoperator/) |
| [IMathParagraph](./imathparagraph/) | Paragrafo matematico che è un contenitore per blocchi matematici ([IMathBlock](./imathblock/)) |
| [IMathParagraphFactory](./imathparagraphfactory/) | Consente di creare un paragrafo matematico |
| [IMathPhantom](./imathphantom/) | Rappresenta un oggetto matematico fantasma (<m:phant>) che influisce sul layout del suo elemento figlio senza necessariamente visualizzarlo. Un fantasma può nascondere l'espressione base mantenendo la sua larghezza, altezza o profondità per allineare formule o riservare spazio. Visibilità e comportamento geometrico sono controllati da proprietà come Show, ZeroWid, ZeroAsc, ZeroDesc e Transp. |
| [IMathPortion](./imathportion/) | Rappresenta una porzione con contesto matematico interno. |
| [IMathRadical](./imathradical/) | Specifica la funzione radicale, composta da una base e da un grado opzionale. Esempio di oggetto radice è \\u221A\\uD835\\uDC65. |
| [IMathRadicalFactory](./imathradicalfactory/) | Consente di creare una radice matematica |
| [IMathRightSubSuperscriptElement](./imathrightsubsuperscriptelement/) | Specifica l'oggetto Sotto/Superindice, composto da una base e da un pedice e un apice posizionati a destra della base. |
| [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) | Consente di creare [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [IMathSubscriptElement](./imathsubscriptelement/) | Specifica l'oggetto pedice, composto da una base e un pedice di dimensioni ridotte posizionato sotto e a destra. |
| [IMathSubscriptElementFactory](./imathsubscriptelementfactory/) | Consente di creare [IMathSubscriptElement](./imathsubscriptelement/) |
| [IMathSuperscriptElement](./imathsuperscriptelement/) | Specifica l'oggetto apice, composto da una base e un apice di dimensioni ridotte posizionato sopra e a destra |
| [IMathSuperscriptElementFactory](./imathsuperscriptelementfactory/) | Consente di creare [IMathSuperscriptElement](./imathsuperscriptelement/) |
| [MathAccent](./mathaccent/) | Specifica la funzione di accento, composta da una base e un segno diacritico combinante. Esempio: \\uD835\\uDC4E\\u0301 |
| [MathAccentFactory](./mathaccentfactory/) | Consente di creare un accento matematico |
| [MathArray](./matharray/) | Specifica un array verticale di equazioni o di qualsiasi oggetto matematico |
| [MathArrayFactory](./matharrayfactory/) | Consente di creare un array matematico |
| [MathBar](./mathbar/) | Specifica la funzione barra, composta da un argomento base e una barra superiore o inferiore |
| [MathBarFactory](./mathbarfactory/) | Consente di creare una barra matematica |
| [MathBlock](./mathblock/) | Specifica un'istanza di testo matematico contenuta all'interno di un [MathParagraph](./mathparagraph/) e che inizia su una propria riga. Tutte le zone matematiche, incluse equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da un blocco matematico. |
| [MathBlockFactory](./mathblockfactory/) | Consente di creare un blocco matematico |
| [MathBorderBox](./mathborderbox/) | Disegna un bordo rettangolare o di altro tipo attorno al [IMathElement](./imathelement/). |
| [MathBorderBoxFactory](./mathborderboxfactory/) | Consente di creare una casella di bordo matematico |
| [MathBox](./mathbox/) | Specifica l'incapsulamento logico (boxing) di un elemento matematico. Ad esempio, un oggetto incapsulato può fungere da emulatore di operatore con o senza punto di allineamento, fungere da punto di interruzione di riga, o essere raggruppato in modo da non consentire interruzioni di riga all'interno. Per esempio, l'operatore \"==\" dovrebbe essere incapsulato per prevenire interruzioni di riga. |
| [MathBoxFactory](./mathboxfactory/) | Consente di creare una casella matematica |
| [MathDelimiter](./mathdelimiter/) | Specifica l'oggetto delimitatore, composto da caratteri di apertura e chiusura (come parentesi tonde, graffe, quadre e barre verticali) e da uno o più elementi matematici al suo interno, separati da un carattere specificato. Esempi: (\\uD835\\uDC652); [\\uD835\\uDC652|\\uD835\\uDC662] |
| [MathDelimiterFactory](./mathdelimiterfactory/) | Consente di creare un delimitatore matematico |
| [MathElementBase](./mathelementbase/) | Classe base per [IMathElement](./imathelement/) con l'implementazione di alcuni metodi comuni a tutte le classi ereditate. Solo per uso interno. La classe ereditata deve essere [IMathElement](./imathelement/). |
| [MathematicalText](./mathematicaltext/) | Testo matematico |
| [MathematicalTextFactory](./mathematicaltextfactory/) | Consente di creare un elemento [MathematicalText](./mathematicaltext/) |
| [MathFraction](./mathfraction/) | Specifica l'oggetto frazione, composto da numeratore e denominatore separati da una barra frazionaria. La barra può essere orizzontale o diagonale, a seconda delle proprietà della frazione. L'oggetto frazione è anche usato per rappresentare la funzione stack, che posiziona un elemento sopra un altro, senza barra frazionaria. |
| [MathFractionFactory](./mathfractionfactory/) | Consente di creare una frazione matematica |
| [MathFunction](./mathfunction/) | Specifica una funzione di un argomento. |
| [MathFunctionFactory](./mathfunctionfactory/) | Consente di creare una funzione matematica |
| [MathGroupingCharacter](./mathgroupingcharacter/) | Specifica un simbolo di raggruppamento sopra o sotto un'espressione, solitamente per evidenziare la relazione tra gli elementi |
| [MathGroupingCharacterFactory](./mathgroupingcharacterfactory/) | Consente di creare un carattere di raggruppamento matematico |
| [MathLeftSubSuperscriptElement](./mathleftsubsuperscriptelement/) | Specifica l'oggetto Sotto/Superindice, composto da una base e da un pedice e un apice posizionati a sinistra della base. |
| [MathLimit](./mathlimit/) | Specifica l'oggetto Limite, composto da testo sulla linea di base e testo di dimensioni ridotte immediatamente sopra o sotto di esso. |
| [MathLimitFactory](./mathlimitfactory/) | Consente di creare [IMathLimit](./imathlimit/) |
| [MathMatrix](./mathmatrix/) | Specifica l'oggetto Matrice, composto da elementi figli disposti in una o più righe e colonne. È importante notare che le matrici non hanno delimitatori incorporati. Per collocare la matrice tra parentesi è necessario usare l'oggetto delimitatore ([IMathDelimiter](./imathdelimiter/)). Gli argomenti nulli possono essere usati per creare spazi vuoti nelle matrici. |
| [MathMatrixFactory](./mathmatrixfactory/) | Consente di creare una matrice matematica |
| [MathNaryOperator](./mathnaryoperator/) | Specifica un oggetto matematico n-ario, come Somma e Integrale. È composto da un operatore, una base (o operando) e limiti superiori e inferiori opzionali. Esempi di operatori n-ari sono: Somma, Unione, Intersezione, Integrale |
| [MathNaryOperatorFactory](./mathnaryoperatorfactory/) | Consente di creare [IMathNaryOperator](./imathnaryoperator/) |
| [MathParagraph](./mathparagraph/) | Paragrafo matematico che è un contenitore per blocchi matematici ([IMathBlock](./imathblock/)) |
| [MathParagraphFactory](./mathparagraphfactory/) | Consente di creare un paragrafo matematico |
| [MathPhantom](./mathphantom/) | Rappresenta un oggetto matematico fantasma (<m:phant>) che influisce sul layout del suo elemento figlio senza necessariamente visualizzarlo. Un fantasma può nascondere l'espressione base mantenendo la sua larghezza, altezza o profondità per allineare formule o riservare spazio. Visibilità e comportamento geometrico sono controllati da proprietà come Show, ZeroWid, ZeroAsc, ZeroDesc e Transp. |
| [MathPortion](./mathportion/) | Rappresenta una porzione con contesto matematico interno. |
| [MathRadical](./mathradical/) | Specifica la funzione radicale, composta da una base e da un grado opzionale. Esempio di oggetto radice è \\u221A\\uD835\\uDC65. |
| [MathRadicalFactory](./mathradicalfactory/) | Consente di creare una radice matematica |
| [MathRightSubSuperscriptElement](./mathrightsubsuperscriptelement/) | Specifica l'oggetto Sotto/Superindice, composto da una base e da un pedice e un apice posizionati a destra della base. |
| [MathRightSubSuperscriptElementFactory](./mathrightsubsuperscriptelementfactory/) | Consente di creare [IMathRightSubSuperscriptElementFactory](./imathrightsubsuperscriptelementfactory/) |
| [MathSubscriptElement](./mathsubscriptelement/) | Specifica l'oggetto pedice, composto da una base e un pedice di dimensioni ridotte posizionato sotto e a destra. |
| [MathSubscriptElementFactory](./mathsubscriptelementfactory/) | Consente di creare [IMathSubscriptElement](./imathsubscriptelement/) |
| [MathSuperscriptElement](./mathsuperscriptelement/) | Specifica l'oggetto apice, composto da una base e un apice di dimensioni ridotte posizionato sopra e a destra |
| [MathSuperscriptElementFactory](./mathsuperscriptelementfactory/) | Consente di creare [IMathSuperscriptElement](./imathsuperscriptelement/) |

## Enumerazioni

| Enum | Descrizione |
| --- | --- |
| [MathDelimiterShape](./mathdelimitershape/) | Specifica la posizione e la dimensione dei delimitatori rispetto al contenuto degli operandi |
| [MathFractionTypes](./mathfractiontypes/) | Tipi di frazione |
| [MathFunctionsOfOneArgument](./mathfunctionsofoneargument/) | Funzioni matematiche comuni di un argomento |
| [MathFunctionsOfTwoArguments](./mathfunctionsoftwoarguments/) | Funzioni matematiche comuni di due argomenti |
| [MathHorizontalAlignment](./mathhorizontalalignment/) | Allineamento orizzontale |
| [MathIntegralTypes](./mathintegraltypes/) | Tipi di integrali matematici |
| [MathJustification](./mathjustification/) | Specifica l'allineamento del paragrafo matematico (una serie di istanze adiacenti di testo matematico all'interno dello stesso paragrafo) |
| [MathLimitLocations](./mathlimitlocations/) | Posizione dei limiti (pedice/apice) negli operatori n-ari. |
| [MathNaryOperatorTypes](./mathnaryoperatortypes/) | Tipi di operatore n-ario [IMathNaryOperator](./imathnaryoperator/) (esclusi gli integrali). Per gli integrali [MathIntegralTypes](./mathintegraltypes/) |
| [MathRowSpacingRule](./mathrowspacingrule/) | Tipo di spaziatura verticale tra le colonne in una matrice o array |
| [MathSpacingRules](./mathspacingrules/) | Tipi di interstizio (spaziatura orizzontale) tra le colonne di una matrice |
| [MathTopBotPositions](./mathtopbotpositions/) | Enumerazione delle posizioni superiore/inferiore |
| [MathVerticalAlignment](./mathverticalalignment/) | Allineamento verticale |