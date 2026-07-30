---
title: AudioFrame
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta una clip audio su una diapositiva.
type: docs
weight: 53
url: /it/aspose.slides/audioframe/
---
## AudioFrame classe

Rappresenta una clip audio su una diapositiva.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto su quello specificato. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Crea e restituisce un array di elementi della forma. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, inclusi NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, inclusi NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Restituisce il valore di aggiustamento di una forma all'indice specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Restituisce una raccolta dei valori di aggiustamento di una forma. Sola lettura [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Restituisce il testo alternativo associato a una forma. Sola lettura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Restituisce il titolo del testo alternativo associato a una forma. Sola lettura [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Restituisce l'indice dell'ultimo tracciato. Sola lettura **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Restituisce il tempo dell'ultimo tracciato. Sola lettura **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Restituisce l'indice del tracciato di avvio. Sola lettura **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Restituisce il tempo del tracciato di avvio. Sola lettura **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La proprietà specifica come una forma verrà renderizzata nella modalità bianco-nero. Sola lettura [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Ottiene la raccolta di sottotitoli chiusi associati al fotogramma audio. Questa proprietà è di sola lettura e restituisce un [ICaptionsCollection](../icaptionscollection/) contenente tutte le tracce dei sottotitoli. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Restituisce il numero di punti di connessione sulla forma. Sola lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Restituisce i dati personalizzati della forma. Sola lettura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Restituisce l'oggetto [EffectFormat](../effectformat/) che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà di effetto. Sola lettura [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Determina se un suono è incorporato in una presentazione. Sola lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Restituisce l'oggetto audio incorporato. Sola lettura [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | Specifica la durata in millisecondi del fade-in iniziale del media. Sola lettura **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | Specifica la durata in millisecondi del fade-out finale del media. Sola lettura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Restituisce l'oggetto [FillFormat](../fillformat/) che contiene le proprietà di formattazione di riempimento per una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà di riempimento. Sola lettura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Restituisce le proprietà del frame della forma. Sola lettura [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Ottiene l'altezza della forma, misurata in punti. Sola lettura **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determina se la forma è nascosta. Sola lettura **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Determina se un [AudioFrame](./) è nascosto. Sola lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Restituisce l'hyperlink definito per il click del mouse. Sola lettura [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Restituisce il gestore degli hyperlink. Sola lettura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Restituisce l'hyperlink definito per il mouse over. Sola lettura [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Determina se il [PictureFrame](../pictureframe/) è un oggetto Cameo o meno. Sola lettura **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Ottiene l'opzione 'Mark as decorative'. Lettura/scrittura **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determina se la forma è raggruppata. Sola lettura **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determina se la forma è TextHolder_PPT. Sola lettura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Restituisce l'oggetto [LineFormat](../lineformat/) che contiene le proprietà di formattazione della linea per una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà di linea. Sola lettura [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Restituisce il nome di un file audio collegato a un [AudioFrame](./). Sola lettura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Restituisce il nome di una forma. Non deve essere nullo. Usa una stringa vuota se necessario. Sola lettura [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Restituisce un identificatore unico a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento. Sola lettura **uint32_t**. Vedi anche [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Restituisce l'oggetto [GroupShape](../groupshape/) padre se la forma è raggruppata. Altrimenti restituisce null. Sola lettura [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Restituisce l'oggetto [PictureFillFormat](../picturefillformat/) per un frame immagine. Sola lettura [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Restituisce i blocchi della forma. Sola lettura [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Restituisce il segnaposto per una forma. Restituisce null se la forma non ha segnaposto. Sola lettura [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Determina se l'audio è in riproduzione attraverso le diapositive. Sola lettura **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Determina se un audio è in loop. Sola lettura **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Restituisce la modalità di riproduzione audio. Sola lettura [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Restituisce la presentazione padre di una diapositiva. Sola lettura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Restituisce le proprietà grezze del frame della forma. Sola lettura [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Restituisce la scala dell'altezza (relativa alla dimensione originale dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Sola lettura **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Restituisce la scala della larghezza (relativa alla dimensione originale dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Sola lettura **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Determina se l'audio viene riavvolto automaticamente all'inizio dopo la riproduzione. Sola lettura **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Restituisce il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Sola lettura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Restituisce i blocchi della forma. Sola lettura [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Restituisce l'oggetto stile della forma. Sola lettura [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Restituisce la diapositiva padre di una forma. Sola lettura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Restituisce l'oggetto [ThreeDFormat](../threedformat/) che contiene le proprietà degli effetti 3D per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà 3D. Sola lettura [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Specifica la durata in millisecondi da rimuovere dalla fine del media durante la riproduzione. Sola lettura **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Specifica la durata in millisecondi da rimuovere dall'inizio del media durante la riproduzione. Sola lettura **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di add-in o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come una chiave unica persistente. Sola lettura **uint32_t**. Vedi anche [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Restituisce il volume audio. Sola lettura [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Restituisce il volume audio in percentuale. Sola lettura **float**. |
| **float** [get_Width](../shape/get_width/)() override | Ottiene la larghezza della forma, misurata in punti. Sola lettura **float**. |
| **float** [get_X](../shape/get_x/)() override | Ottiene la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Sola lettura **float**. |
| **float** [get_Y](../shape/get_y/)() override | Ottiene la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Sola lettura **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma più in fondo all'ordine Z, e Shapes[Shapes.Count - 1] restituisce la forma più in alto nell'ordine Z. Sola lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Restituisce la copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Restituisce la miniatura della forma. Per impostazione predefinita viene utilizzato il tipo di limiti della miniatura [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Restituisce la miniatura della forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente il cloning di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definisce che questa forma non è un segnaposto. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Imposta il testo alternativo associato a una forma. Scrivi [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Imposta il titolo del testo alternativo associato a una forma. Scrivi [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Imposta l'indice dell'ultimo tracciato. Scrivi **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Imposta il tempo dell'ultimo tracciato. Scrivi **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Imposta l'indice del tracciato di avvio. Scrivi **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Imposta il tempo del tracciato di avvio. Scrivi **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | La proprietà specifica come una forma verrà renderizzata nella modalità bianco-nero. Scrivi [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Imposta l'oggetto audio incorporato. Scrivi [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Specifica la durata in millisecondi del fade-in iniziale del media. Scrivi **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Specifica la durata in millisecondi del fade-out finale del media. Scrivi **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Imposta le proprietà del frame della forma. Scrivi [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Imposta l'altezza della forma, misurata in punti. Scrivi **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Determina se la forma è nascosta. Scrivi **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Determina se un [AudioFrame](./) è nascosto. Scrivi **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Imposta l'hyperlink definito per il click del mouse. Scrivi [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Imposta l'hyperlink definito per mouse over. Scrivi [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Imposta l'opzione 'Mark as decorative'. Lettura/scrittura **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Imposta il nome di un file audio collegato a un [AudioFrame](./). Scrivi [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Imposta il nome di una forma. Non deve essere nullo. Usa una stringa vuota se necessario. Scrivi [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Determina se l'audio è in riproduzione attraverso le diapositive. Scrivi **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Determina se un audio è in loop. Scrivi **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Imposta la modalità di riproduzione audio. Scrivi [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Imposta le proprietà grezze del frame della forma. Scrivi [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Imposta la scala dell'altezza (relativa alla dimensione originale dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Scrivi **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Imposta la scala della larghezza (relativa alla dimensione originale dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Scrivi **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Determina se l'audio viene riavvolto automaticamente all'inizio dopo la riproduzione. Scrivi **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Scrivi **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Specifica la durata in millisecondi da rimuovere dalla fine del media durante la riproduzione. Scrivi **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Specifica la durata in millisecondi da rimuovere dall'inizio del media durante la riproduzione. Scrivi **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Imposta il volume audio. Scrivi [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Imposta il volume audio in percentuale. Scrivi **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Imposta la larghezza della forma, misurata in punti. Scrivi **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Scrivi **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Scrivi **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Aggiorna la geometria della forma dall'oggetto [IGeometryPath](../igeometrypath/). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([ShapeType](../shapetype/)) in [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Aggiorna la geometria della forma da un array di [IGeometryPath](../igeometrypath/). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([ShapeType](../shapetype/)) in [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di cambiare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; usare smart pointer o ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Salva il contenuto di [Shape](../shape/) come file SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Salva il contenuto di [Shape](../shape/) come file SVG. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni

Gli esempi seguenti mostrano come modificare le Opzioni di riproduzione di [Audio](../audio/).  
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [PictureFrame](../pictureframe/)
* Classe [IAudioFrame](../iaudioframe/)
* Spazio dei nomi [Aspose::Slides](../)
* Library [Aspose.Slides](../../)