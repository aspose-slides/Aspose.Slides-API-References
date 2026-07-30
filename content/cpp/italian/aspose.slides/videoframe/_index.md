---
title: VideoFrame
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta una clip video su una diapositiva.
type: docs
weight: 5552
url: /it/aspose.slides/videoframe/
---
## VideoFrame classe

Rappresenta una clip video su una diapositiva.

```cpp
class VideoFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IVideoFrame
```

## Metodi

| Method | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Aggiunge un nuovo placeholder se non esiste e imposta le proprietà del placeholder su uno specificato. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Crea e restituisce un array degli elementi di shape. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Restituisce il valore di regolazione di shape all'indice specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Restituisce una collezione dei valori di regolazione di shape. Sola lettura [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Restituisce il testo alternativo associato a una shape. Lettura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Restituisce il titolo del testo alternativo associato a una shape. Lettura [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La proprietà specifica come una shape verrà renderizzata in modalità bianco-nero. Lettura [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Ottiene la collezione di sottotitoli chiusi associati al video frame. Questa proprietà è sola lettura e restituisce un [ICaptionsCollection](../icaptionscollection/) contenente tutte le tracce dei sottotitoli. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Restituisce il numero di punti di connessione su shape. Sola lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Restituisce i dati personalizzati di shape. Sola lettura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Restituisce l'oggetto [EffectFormat](../effectformat/) che contiene gli effetti pixel applicati a shape. Nota: può restituire null per alcuni tipi di shape che non hanno proprietà di effetto. Sola lettura [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() override | Restituisce l'oggetto video incorporato. Lettura [IVideo](../ivideo/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Restituisce l'oggetto [FillFormat](../fillformat/) che contiene le proprietà di formattazione di riempimento per una shape. Nota: può restituire null per alcuni tipi di shape che non hanno proprietà di riempimento. Sola lettura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Restituisce le proprietà del frame di shape. Lettura [IShapeFrame](../ishapeframe/). |
| **bool** [get_FullScreenMode](./get_fullscreenmode/)() override | Determina se un video è mostrato in modalità a schermo intero. Lettura **bool**. |
| **float** [get_Height](../shape/get_height/)() override | Ottiene l'altezza di shape, misurata in punti. Lettura **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determina se shape è nascosta. Lettura **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Determina se un [VideoFrame](./) è nascosto. Lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Restituisce l'hyperlink definito per il click del mouse. Lettura [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Restituisce il gestore degli hyperlink. Sola lettura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Restituisce l'hyperlink definito per il mouse over. Lettura [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Determina se il [PictureFrame](../pictureframe/) è un oggetto Cameo o no. Sola lettura **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Ottiene l'opzione 'Mark as decorative' Lettura/scrittura **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determina se shape è raggruppata. Sola lettura **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determina se shape è TextHolder_PPT. Sola lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Restituisce l'oggetto [LineFormat](../lineformat/) che contiene le proprietà di formattazione della linea per una shape. Nota: può restituire null per alcuni tipi di shape che non hanno proprietà di linea. Sola lettura [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Restituisce il nome di un file video collegato a [VideoFrame](./). Lettura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Restituisce il nome di una shape. Deve non essere null. Usa una stringa vuota se necessario. Lettura [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Restituisce un identificatore univoco a livello di diapositiva che rimane costante per la durata di shape e consente a PowerPoint o al codice interop di fare riferimento a shape in modo affidabile da qualsiasi punto del documento. Sola lettura **uint32_t**. Vedi anche [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Restituisce l'oggetto padre [GroupShape](../groupshape/) se shape è raggruppata. Altrimenti restituisce null. Sola lettura [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Restituisce l'oggetto [PictureFillFormat](../picturefillformat/) per un frame immagine. Sola lettura [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Restituisce i lock di shape. Sola lettura [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Restituisce il placeholder per una shape. Restituisce null se shape non ha placeholder. Sola lettura [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Determina se un video è in loop. Lettura **bool**. |
| [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Restituisce la modalità di riproduzione video. Lettura [VideoPlayModePreset](../videoplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Restituisce la presentazione padre di una diapositiva. Sola lettura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Restituisce le proprietà grezze del frame di shape. Lettura [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Restituisce la scala dell'altezza (relativa alla dimensione originale dell'immagine) del frame immagine. Valore 1.0 corrisponde al 100%. Lettura **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Restituisce la scala della larghezza (relativa alla dimensione originale dell'immagine) del frame immagine. Valore 1.0 corrisponde al 100%. Lettura **float**. |
| **bool** [get_RewindVideo](./get_rewindvideo/)() override | Determina se un video è riavvolto automaticamente all'inizio non appena il film termina la riproduzione. Lettura **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Restituisce il numero di gradi di rotazione della shape specificata attorno all'asse z. Un valore positivo indica rotazione oraria; un valore negativo indica rotazione antioraria. Lettura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Restituisce i lock di shape. Sola lettura [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Restituisce l'oggetto di stile di shape. Sola lettura [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Restituisce la diapositiva padre di una shape. Sola lettura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Restituisce l'oggetto [ThreeDFormat](../threedformat/) che contiene le proprietà dell'effetto 3D per una shape. Nota: può restituire null per alcuni tipi di shape che non hanno proprietà 3D. Sola lettura [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Taglio finale [ms] |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Taglio iniziale [ms] |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di add-in o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come chiave unica persistente. Sola lettura **uint32_t**. Vedi anche [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Restituisce il volume audio. Lettura [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_Width](../shape/get_width/)() override | Ottiene la larghezza di shape, misurata in punti. Lettura **float**. |
| **float** [get_X](../shape/get_x/)() override | Ottiene la coordinata x dell'angolo superiore sinistro di shape, misurata in punti. Lettura **float**. |
| **float** [get_Y](../shape/get_y/)() override | Ottiene la coordinata y dell'angolo superiore sinistro di shape, misurata in punti. Lettura **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Restituisce la posizione di una shape nell'ordine Z. Shapes[0] restituisce la shape in fondo all'ordine Z, e Shapes[Shapes.Count - 1] restituisce la shape in cima all'ordine Z. Sola lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Restituisce una shape placeholder di base (shape dal layout e/o slide master da cui la shape corrente è ereditata). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Restituisce la copia del percorso della shape geometrica. Le coordinate sono relative all'angolo superiore sinistro della shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Restituisce la miniatura della shape. Il tipo di bounds della miniatura della shape [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) è usato per default. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Restituisce la miniatura della shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Ottiene i limiti visivi della shape calcolati dal suo contenuto renderizzato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() statement di C# per il blocco. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, davvero, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie di subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, davvero, semplicemente inizializza un nuovo oggetto e consente la costruzione di copie di subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definisce che questa shape non è un placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Imposta il testo alternativo associato a una shape. Scrivi [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Imposta il titolo del testo alternativo associato a una shape. Scrivi [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | La proprietà specifica come una shape sarà renderizzata in modalità bianco-nero. Scrivi [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | Imposta l'oggetto video incorporato. Scrivi [IVideo](../ivideo/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Imposta le proprietà del frame di shape. Scrivi [IShapeFrame](../ishapeframe/). |
| void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) override | Determina se un video è mostrato in modalità a schermo intero. Scrivi **bool**. |
| void [set_Height](../shape/set_height/)(**float**) override | Imposta l'altezza di shape, misurata in punti. Scrivi **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Determina se shape è nascosta. Scrivi **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Determina se un [VideoFrame](./) è nascosto. Scrivi **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Imposta l'hyperlink definito per il click del mouse. Scrivi [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Imposta l'hyperlink definito per il mouse over. Scrivi [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Imposta l'opzione 'Mark as decorative' Lettura/scrittura **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Imposta il nome di un file video collegato a [VideoFrame](./). Scrivi [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Imposta il nome di una shape. Deve non essere null. Usa una stringa vuota se necessario. Scrivi [System::String](../../system/string/). |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Determina se un video è in loop. Scrivi **bool**. |
| void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) override | Imposta la modalità di riproduzione video. Scrivi [VideoPlayModePreset](../videoplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Imposta le proprietà grezze del frame di shape. Scrivi [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Imposta la scala dell'altezza (relativa alla dimensione originale dell'immagine) del frame immagine. Valore 1.0 corrisponde al 100%. Scrivi **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Imposta la scala della larghezza (relativa alla dimensione originale dell'immagine) del frame immagine. Valore 1.0 corrisponde al 100%. Scrivi **float**. |
| void [set_RewindVideo](./set_rewindvideo/)(**bool**) override | Determina se un video è riavvolto automaticamente all'inizio non appena il film termina la riproduzione. Scrivi **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Imposta il numero di gradi di rotazione della shape specificata attorno all'asse z. Un valore positivo indica rotazione oraria; un valore negativo indica rotazione antioraria. Scrivi **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Taglio finale [ms] |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Taglio iniziale [ms] |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Imposta il volume audio. Scrivi [AudioVolumeMode](../audiovolumemode/). |
| void [set_Width](../shape/set_width/)(**float**) override | Imposta la larghezza di shape, misurata in punti. Scrivi **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Imposta la coordinata x dell'angolo superiore sinistro di shape, misurata in punti. Scrivi **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Imposta la coordinata y dell'angolo superiore sinistro di shape, misurata in punti. Scrivi **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Aggiorna la geometria di shape dal oggetto [IGeometryPath](../igeometrypath/). Le coordinate devono essere relative all'angolo superiore sinistro della shape. Cambia il tipo di shape ([ShapeType](../shapetype/)) in [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Aggiorna la geometria di shape da un array di [IGeometryPath](../igeometrypath/). Le coordinate devono essere relative all'angolo superiore sinistro della shape. Cambia il tipo di shape ([ShapeType](../shapetype/)) in [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'argomento template n-esimo a un weak pointer (piuttosto che shared). Consente di cambiare i pointer nei contenitori in modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() statement di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Salva il contenuto di [Shape](../shape/) come file SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Salva il contenuto di [Shape](../shape/) come file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [PictureFrame](../pictureframe/)
* Classe [IVideoFrame](../ivideoframe/)
* Namespace [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)