---
title: GraphicsPath
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un insieme di linee e curve collegate. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e usare tale puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 66
url: /it/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath classe

Rappresenta un insieme di linee e curve connesse. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare tale puntatore per passarlo alle funzioni come argomento.

```cpp
class GraphicsPath : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Aggiunge l'arco ellittico specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Aggiunge l'arco ellittico specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Aggiunge l'arco ellittico specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Aggiunge l'arco ellittico specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Aggiunge la curva di Bézier cubica specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Aggiunge la curva di Bézier cubica specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Aggiunge la curva di Bézier cubica specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Aggiunge la curva di Bézier cubica specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Aggiunge una sequenza di curve di Bézier cubiche collegate alla figura corrente. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Aggiunge una sequenza di curve di Bézier cubiche collegate alla figura corrente. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Aggiunge la curva chiusa specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Aggiunge la curva chiusa specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Aggiunge la curva specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Aggiunge la curva specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Aggiunge la curva specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Aggiunge la curva specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Aggiunge l'ellisse specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Aggiunge l'ellisse specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Aggiunge l'ellisse specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Aggiunge l'ellisse specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Aggiunge la linea specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Aggiunge la linea specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddLine](./addline/)(int, int, int, int) | Aggiunge la linea specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Aggiunge la linea specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Aggiunge la serie di segmenti di linea connessi specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Aggiunge la serie di segmenti di linea connessi specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Aggiunge il percorso specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Aggiunge il contorno della forma a torta specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Aggiunge il contorno della forma a torta specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Aggiunge il contorno della forma a torta specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Aggiunge il poligono specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Aggiunge il poligono specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Aggiunge il rettangolo specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Aggiunge il rettangolo specificato al percorso rappresentato dall'oggetto corrente. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Aggiunge la serie di rettangoli specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Aggiunge la serie di rettangoli specificata al percorso rappresentato dall'oggetto corrente. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Aggiunge una stringa di testo al percorso rappresentato dall'oggetto corrente. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Aggiunge una stringa di testo al percorso rappresentato dall'oggetto corrente. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Aggiunge una stringa di testo al percorso rappresentato dall'oggetto corrente. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Aggiunge una stringa di testo al percorso rappresentato dall'oggetto corrente. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Crea una copia dell'oggetto corrente. |
| void [CloseAllFigures](./closeallfigures/)() | Chiude tutte le figure aperte e ne avvia una nuova. |
| void [CloseFigure](./closefigure/)() | Chiude la figura corrente e ne avvia una nuova. |
| void [Dispose](./dispose/)() | Rilascia tutte le risorse del sistema operativo acquisite dall'oggetto corrente. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri floating-point in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri floating-point in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| void [Flatten](./flatten/)() | Appiattisce ogni curva nel percorso convertendola in una serie di linee connesse. Viene usato il valore di piattezza 0,25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Appiattisce ogni curva nel percorso convertendola in una serie di linee connesse. Viene usato il valore di piattezza 0,25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Appiattisce ogni curva nel percorso convertendola in una serie di linee connesse. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Restituisce la modalità di riempimento dell'oggetto corrente. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Restituisce un oggetto [PathData](../pathdata/) contenente i punti che compongono un percorso rappresentato dall'oggetto corrente e i loro tipi. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Restituisce un array che contiene i punti che compongono un percorso rappresentato dall'oggetto corrente. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Restituisce un array che contiene i valori che indicano i tipi dei punti che compongono un percorso rappresentato dall'oggetto corrente. |
| int [get_PointCount](./get_pointcount/)() const | Restituisce il numero di punti nel percorso rappresentato dall'oggetto corrente. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Restituisce un oggetto [RectangleF](../../system.drawing/rectanglef/) che rappresenta un rettangolo che delimita il percorso rappresentato dall'oggetto corrente quando è trasformato con la matrice specificata. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Restituisce un valore che è una combinazione bitwise di valori Detail::FigureType che indica i tipi di figure contenuti nel percorso rappresentato dall'oggetto corrente. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Restituisce un oggetto [PointF](../../system.drawing/pointf/) che rappresenta l'ultimo punto nel percorso. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Costruisce una nuova istanza della classe [GraphicsPath](./) con la modalità di riempimento specificata. |
| [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Costruisce una nuova istanza dell'oggetto [GraphicsPath](./) che rappresenta il percorso specificato. |
| [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Costruisce una nuova istanza dell'oggetto [GraphicsPath](./) che rappresenta il percorso specificato. |
| [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Indica se il punto specificato è contenuto (sotto) il contorno di questo [GraphicsPath](./) quando disegnato con il [Pen](../../system.drawing/pen/) specificato. NON IMPLEMENTATO. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Determina se il punto specificato è contenuto nel percorso rappresentato dall'oggetto corrente. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Determina se il punto specificato è contenuto nel percorso rappresentato dall'oggetto corrente. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita il clonaggio di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la copia dei sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e abilita la copia dei sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [Reset](./reset/)() | Svuota il percorso rimuovendo tutti i punti. |
| void [Reverse](./reverse/)() | Inverte l'ordine dei punti nell'array PathPoints di questo [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Imposta la modalità di riempimento dell'oggetto corrente. |
| void [SetMarkers](./setmarkers/)() | NON IMPLEMENTATO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [StartFigure](./startfigure/)() | Avvia una nuova figura. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Trasforma il percorso rappresentato dall'oggetto corrente applicando la matrice di trasformazione specificata. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare invece smart pointer o ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Sostituisce questo percorso con un contorno attorno al percorso originale. |
| [~GraphicsPath](./~graphicspath/)() | Distruttore. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [System::Drawing::Drawing2D](../)
* Libreria [Aspose.Slides](../../)