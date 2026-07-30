---
title: AutoShape
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta un AutoShape.
type: docs
weight: 66
url: /it/aspose.slides/autoshape/
---
## AutoShape classe

Rappresenta un [AutoShape](./).

```cpp
class AutoShape : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IAutoShape
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Aggiunge un nuovo placeholder se non ne esiste e imposta le proprietà del placeholder a uno specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [AddTextFrame](./addtextframe/)([System::String](../../system/string/)) override | Aggiunge un nuovo [TextFrame](../textframe/) a una forma. Se la forma ha già [TextFrame](../textframe/) cambia semplicemente il suo testo. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Crea e restituisce un array degli elementi della forma. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Restituisce il valore di aggiustamento di una forma all'indice specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Restituisce una raccolta dei valori di aggiustamento della forma. Solo lettura [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Restituisce il testo alternativo associato a una forma. Solo lettura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Restituisce il titolo del testo alternativo associato a una forma. Solo lettura [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShapeLock](../iautoshapelock/)\> [get_AutoShapeLock](./get_autoshapelock/)() override | Restituisce i blocchi dell'autoshape. Solo lettura [IAutoShapeLock](../iautoshapelock/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La proprietà specifica come una forma verrà renderizzata in modalità bianco e nero. Solo lettura [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Restituisce il numero di punti di connessione sulla forma. Solo lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Restituisce i dati personalizzati della forma. Solo lettura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Restituisce l'oggetto [EffectFormat](../effectformat/) che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di effetto. Solo lettura [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Restituisce l'oggetto [FillFormat](../fillformat/) che contiene le proprietà di formattazione riempimento per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di riempimento. Solo lettura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Restituisce le proprietà del frame della forma. Solo lettura [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Ottiene l'altezza della forma, misurata in punti. Solo lettura **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determina se la forma è nascosta. Solo lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Restituisce il collegamento ipertestuale definito per il click del mouse. Solo lettura [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Restituisce il gestore dei collegamenti ipertestuali. Solo lettura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Restituisce il collegamento ipertestuale definito per il passaggio del mouse. Solo lettura [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Ottiene l'opzione 'Mark as decorative'. Lettura/scrittura **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determina se la forma è raggruppata. Solo lettura **bool**. |
| **bool** [get_IsTextBox](./get_istextbox/)() override | Specifica se la forma è una casella di testo. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determina se la forma è TextHolder_PPT. Solo lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Restituisce l'oggetto [LineFormat](../lineformat/) che contiene le proprietà di formattazione linea per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di linea. Solo lettura [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Restituisce il nome di una forma. Deve essere non nullo. Usa una stringa vuota se necessario. Solo lettura [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Restituisce un identificatore unico a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento alla forma da qualsiasi punto del documento. Solo lettura **uint32_t**. Vedi anche [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Restituisce l'oggetto genitore [GroupShape](../groupshape/) se la forma è raggruppata. Altrimenti restituisce null. Solo lettura [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Restituisce il placeholder per una forma. Restituisce null se la forma non ha placeholder. Solo lettura [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Restituisce la presentazione genitore di una diapositiva. Solo lettura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Restituisce le proprietà grezze del frame della forma. Solo lettura [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Restituisce il numero di gradi di rotazione della forma attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Solo lettura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Restituisce i blocchi della forma. Solo lettura [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Restituisce l'oggetto stile della forma. Solo lettura [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../geometryshape/get_shapetype/)() override | Restituisce il tipo predefinito di geometria. Nota: al cambiamento del valore tutti i valori di aggiustamento torneranno ai loro valori predefiniti. Solo lettura [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Restituisce la diapositiva genitore di una forma. Solo lettura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Restituisce l'oggetto [TextFrame](../textframe/) per il [AutoShape](./). Solo lettura [ITextFrame](../itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Restituisce l'oggetto [ThreeDFormat](../threedformat/) che contiene le proprietà di effetto 3D per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà 3D. Solo lettura [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Restituisce un identificatore interno a livello di presentazione destinato all'uso da componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come una chiave unica persistente. Solo lettura **uint32_t**. Vedi anche [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UseBackgroundFill](./get_usebackgroundfill/)() override | Determina se questo autoshape debba essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato riempimento. Solo lettura **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Ottiene la larghezza della forma, misurata in punti. Solo lettura **float**. |
| **float** [get_X](../shape/get_x/)() override | Ottiene la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Solo lettura **float**. |
| **float** [get_Y](../shape/get_y/)() override | Ottiene la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Solo lettura **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Restituisce la posizione di una forma nell'ordine z. Shapes[0] restituisce la forma più indietro nell'ordine z, e Shapes[Shapes.Count - 1] restituisce la forma più in primo piano. Solo lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Restituisce una forma placeholder di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Restituisce la copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Restituisce la miniatura della forma. Il tipo di limiti della miniatura della forma [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) è usato per impostazione predefinita. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Restituisce la miniatura della forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C# per il locking. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, ma inizializza un nuovo oggetto e abilita la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso delle stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definisce che questa forma non è un placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Imposta il testo alternativo associato a una forma. Scrivi [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Imposta il titolo del testo alternativo associato a una forma. Scrivi [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Specifica come una forma verrà renderizzata in modalità bianco e nero. Scrivi [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Imposta le proprietà del frame della forma. Scrivi [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Imposta l'altezza della forma, misurata in punti. Scrivi **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Determina se la forma è nascosta. Scrivi **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Imposta il collegamento ipertestuale definito per il click del mouse. Scrivi [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Imposta il collegamento ipertestuale definito per il passaggio del mouse. Scrivi [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Imposta l'opzione 'Mark as decorative'. Lettura/scrittura **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Imposta il nome di una forma. Deve essere non nullo. Usa una stringa vuota se necessario. Scrivi [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Imposta le proprietà grezze del frame della forma. Scrivi [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Imposta il numero di gradi di rotazione della forma attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Scrivi **float**. |
| void [set_ShapeType](../geometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | Imposta il tipo predefinito di geometria. Nota: al cambiamento del valore tutti i valori di aggiustamento torneranno ai loro valori predefiniti. Scrivi [Slides::ShapeType](../shapetype/). |
| void [set_UseBackgroundFill](./set_usebackgroundfill/)(**bool**) override | Determina se questo autoshape debba essere riempito con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato riempimento. Scrivi **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Imposta la larghezza della forma, misurata in punti. Scrivi **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Scrivi **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Scrivi **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Aggiorna la geometria della forma dall'oggetto [IGeometryPath](../igeometrypath/). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([ShapeType](../shapetype/)) in [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Aggiorna la geometria della forma da un array di [IGeometryPath](../igeometrypath/). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([ShapeType](../shapetype/)) in [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento template n-esimo come puntatore debole (invece che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa il blocco lock() di C# per lo sblocco. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Salva il contenuto di [Shape](../shape/) come file SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Salva il contenuto di [Shape](../shape/) come file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [GeometryShape](../geometryshape/)
* Classe [IAutoShape](../iautoshape/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)