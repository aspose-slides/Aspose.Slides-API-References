---
title: IShape
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta una forma su una diapositiva.
type: docs
weight: 3641
url: /it/aspose.slides/ishape/
---
## IShape classe


Rappresenta una forma su una diapositiva.

```cpp
class IShape : public virtual Aspose::Slides::ISlideComponent,
               public Aspose::Slides::IHyperlinkContainer
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Aggiunge un nuovo segnaposto se non ce ne è e imposta le proprietà del segnaposto su quello specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() | Restituisce il testo alternativo associato a una forma. Leggi [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() | Restituisce il titolo del testo alternativo associato a una forma. Leggi [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() | La proprietà specifica come una forma verrà renderizzata in modalità di visualizzazione in bianco e nero. Leggi [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() | Restituisce il numero di punti di collegamento sulla forma. Solo lettura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | Restituisce i dati personalizzati della forma. Solo lettura [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Restituisce l'oggetto [EffectFormat](../effectformat/) che contiene gli effetti pixel applicati a una forma. Solo lettura [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Restituisce l'oggetto [FillFormat](../fillformat/) che contiene le proprietà di formattazione del riempimento per una forma. Solo lettura [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() | Restituisce le proprietà del frame della forma. Leggi [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](./get_height/)() | Ottiene l'altezza della forma, misurata in punti. Leggi **float**. |
| virtual **bool** [get_Hidden](./get_hidden/)() | Determina se la forma è nascosta. Leggi **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Restituisce il collegamento ipertestuale definito per il clic del mouse. Leggi [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Gestore dei collegamenti ipertestuali Solo lettura [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Restituisce il collegamento ipertestuale definito per il passaggio del mouse. Leggi [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](./get_isdecorative/)() | Ottiene l'opzione 'Marca come decorativa' Lettura/scrittura **bool**. |
| virtual **bool** [get_IsGrouped](./get_isgrouped/)() | Determina se la forma è raggruppata. Solo lettura **bool**. |
| virtual **bool** [get_IsTextHolder](./get_istextholder/)() | Determina se la forma è TextHolder. Solo lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Restituisce l'oggetto [LineFormat](../lineformat/) che contiene le proprietà di formattazione della linea per una forma. Solo lettura [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | Restituisce il nome di una forma. Leggi [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() | Restituisce un identificatore univoco a livello di diapositiva che rimane costante per tutta la durata della forma e permette a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento. Solo lettura **uint32_t**. Vedi anche [IShape::get_UniqueId](./get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() | Restituisce l'oggetto genitore [GroupShape](../groupshape/) se la forma è raggruppata. Altrimenti restituisce null. Solo lettura [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() | Restituisce il segnaposto per una forma. Solo lettura [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Restituisce la presentazione. Solo lettura [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() | Restituisce le proprietà grezze del frame della forma. Leggi [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](./get_rotation/)() | Restituisce il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Leggi **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() | Restituisce i blocchi della forma. Solo lettura [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Restituisce la diapositiva di base. Solo lettura [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Restituisce l'oggetto [ThreeDFormat](../threedformat/) che contiene le proprietà di formattazione della linea per una forma. Solo lettura [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](./get_uniqueid/)() | Restituisce un identificatore interno, a livello di presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato una chiave univoca persistente. Solo lettura **uint32_t**. Vedi anche [IShape::get_OfficeInteropShapeId](./get_officeinteropshapeid/). |
| virtual **float** [get_Width](./get_width/)() | Ottiene la larghezza della forma, misurata in punti. Leggi **float**. |
| virtual **float** [get_X](./get_x/)() | Ottiene la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Leggi **float**. |
| virtual **float** [get_Y](./get_y/)() | Ottiene la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Leggi **float**. |
| virtual **int32_t** [get_ZOrderPosition](./get_zorderposition/)() | Restituisce la posizione di una forma nell'ordine z. Shapes[0] restituisce la forma più in fondo nell'ordine z, e Shapes[Shapes.Count - 1] restituisce la forma più in avanti nell'ordine z. Solo lettura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](./)\> [GetBasePlaceholder](./getbaseplaceholder/)() | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() | Restituisce la miniatura della forma. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) il tipo dei limiti della miniatura della forma è usato per impostazione predefinita. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Restituisce la miniatura della forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, davvero, inizializza solo il nuovo oggetto e abilita la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, davvero, inizializza solo il nuovo oggetto e abilita la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [RemovePlaceholder](./removeplaceholder/)() | Definisce che questa forma non è un segnaposto. |
| virtual void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) | Imposta il testo alternativo associato a una forma. Scrivi [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) | Imposta il titolo del testo alternativo associato a una forma. Scrivi [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | La proprietà specifica come una forma verrà renderizzata in modalità di visualizzazione in bianco e nero. Scrivi [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Imposta le proprietà del frame della forma. Scrivi [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](./set_height/)(**float**) | Imposta l'altezza della forma, misurata in punti. Scrivi **float**. |
| virtual void [set_Hidden](./set_hidden/)(**bool**) | Determina se la forma è nascosta. Scrivi **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Imposta il collegamento ipertestuale definito per il clic del mouse. Scrivi [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Imposta il collegamento ipertestuale definito per il passaggio del mouse. Scrivi [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](./set_isdecorative/)(**bool**) | Imposta l'opzione 'Marca come decorativa' Lettura/scrittura **bool**. |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | Imposta il nome di una forma. Scrivi [System::String](../../system/string/). |
| virtual void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Imposta le proprietà grezze del frame della forma. Scrivi [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](./set_rotation/)(**float**) | Imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Scrivi **float**. |
| virtual void [set_Width](./set_width/)(**float**) | Imposta la larghezza della forma, misurata in punti. Scrivi **float**. |
| virtual void [set_X](./set_x/)(**float**) | Imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Scrivi **float**. |
| virtual void [set_Y](./set_y/)(**float**) | Imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Scrivi **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello come puntatore debole (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Salva il contenuto di [Shape](../shape/) come file SVG. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Salva il contenuto di [Shape](../shape/) come file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [ISlideComponent](../islidecomponent/)
* Classe [IHyperlinkContainer](../ihyperlinkcontainer/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)