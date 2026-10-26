---
title: VideoFrame class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/videoframe/
---
## classe VideoFrame

Rappresenta una clip video su una diapositiva.

**Eredità:**[`VideoFrame`](/slides/python-net/it/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/it/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo VideoFrame espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/videoframe/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Sola lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/videoframe/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Sola lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/videoframe/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/videoframe/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/videoframe/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/videoframe/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di linea.<br/>            Sola lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/videoframe/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà degli effetti 3d per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà 3d.<br/>            Sola lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/videoframe/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di effetto.<br/>            Sola lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/videoframe/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di riempimento.<br/>            Sola lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/videoframe/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il click del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/videoframe/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/videoframe/hyperlink_manager/) | Restituisce il gestore dei collegamenti ipertestuali.<br/>            Sola lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides/videoframe/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/videoframe/z_order_position/) | Restituisce la posizione di una forma nell'ordine Z.<br/>            Shapes[0] restituisce la forma più indietro nell'ordine Z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma più in avanti nell'ordine Z.<br/>            Sola lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/videoframe/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Sola lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/videoframe/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo<br/>            indica rotazione in senso antiorario.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides/videoframe/x/) | Restituisce o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/videoframe/y/) | Restituisce o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/videoframe/width/) | Restituisce o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/videoframe/height/) | Restituisce o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/videoframe/black_white_mode/) | La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero.<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides/videoframe/unique_id/) | Restituisce un identificatore interno, limitato alla presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato<br/>            come una chiave unica persistente.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/videoframe/office_interop_shape_id/) | Restituisce un identificatore univoco limitato alla diapositiva che rimane costante per tutta la durata della forma e<br/>            consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides/videoframe/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/videoframe/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides/videoframe/name/) | Restituisce o imposta il nome di una forma.<br/>            Non deve essere None. Usa una stringa vuota se necessario.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/videoframe/is_decorative/) | Restituisce o imposta l'opzione 'Segna come decorativo'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/videoframe/shape_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IPictureFrameLock`](/slides/python-net/it/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/videoframe/is_grouped/) | Determina se la forma è raggruppata.<br/>            Sola lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides/videoframe/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Sola lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/videoframe/slide/) | Restituisce la diapositiva genitore della forma.<br/>            Sola lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/videoframe/presentation/) | Restituisce la presentazione genitore della diapositiva.<br/>            Sola lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/it/aspose.slides/videoframe/shape_style/) | Restituisce l'oggetto stile della forma.<br/>            Sola lettura [`IShapeStyle`](/slides/python-net/it/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/it/aspose.slides/videoframe/shape_type/) | Restituisce o imposta il tipo AutoShape per un PictureFrame.<br/>            Sono consentiti tutti gli elementi del set [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype), <br/>            eccetto tutti i tipi di linee:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lettura/scrittura [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/it/aspose.slides/videoframe/adjustments/) | Restituisce una collezione dei valori di regolazione della forma.<br/>            Sola lettura [`IAdjustValueCollection`](/slides/python-net/it/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/it/aspose.slides/videoframe/picture_frame_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IPictureFrameLock`](/slides/python-net/it/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/it/aspose.slides/videoframe/picture_format/) | Restituisce l'oggetto PictureFillFormat per un frame immagine.<br/>            Sola lettura [`IPictureFillFormat`](/slides/python-net/it/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/it/aspose.slides/videoframe/relative_scale_height/) | Restituisce o imposta la scala dell'altezza (relativa alle dimensioni originali dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%.<br/>            Lettura/scrittura **float**. |
| [`relative_scale_width`](/slides/python-net/it/aspose.slides/videoframe/relative_scale_width/) | Restituisce o imposta la scala della larghezza (relativa alle dimensioni originali dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%.<br/>            Lettura/scrittura **float**. |
| [`is_cameo`](/slides/python-net/it/aspose.slides/videoframe/is_cameo/) | Determina se il PictureFrame è un oggetto Cameo o no.<br/>            Sola lettura **bool**. |
| [`rewind_video`](/slides/python-net/it/aspose.slides/videoframe/rewind_video/) | Determina se un video è automaticamente riavvolto all'inizio<br/>            non appena il filmato ha terminato la riproduzione.<br/>            Lettura/scrittura **bool**. |
| [`play_loop_mode`](/slides/python-net/it/aspose.slides/videoframe/play_loop_mode/) | Determina se un video è in loop.<br/>            Lettura/scrittura **bool**. |
| [`hide_at_showing`](/slides/python-net/it/aspose.slides/videoframe/hide_at_showing/) | Determina se un VideoFrame è nascosto.<br/>            Lettura/scrittura **bool**. |
| [`volume`](/slides/python-net/it/aspose.slides/videoframe/volume/) | Restituisce o imposta il volume audio.<br/>            Lettura/scrittura [`AudioVolumeMode`](/slides/python-net/it/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/it/aspose.slides/videoframe/play_mode/) | Restituisce o imposta la modalità di riproduzione video.<br/>            Lettura/scrittura [`VideoPlayModePreset`](/slides/python-net/it/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/it/aspose.slides/videoframe/full_screen_mode/) | Determina se un video è mostrato in modalità a schermo intero.<br/>            Lettura/scrittura **bool**. |
| [`link_path_long`](/slides/python-net/it/aspose.slides/videoframe/link_path_long/) | Restituisce o imposta il nome di un file video collegato a un VideoFrame.<br/>            Lettura/scrittura **str**. |
| [`embedded_video`](/slides/python-net/it/aspose.slides/videoframe/embedded_video/) | Restituisce o imposta l'oggetto video incorporato.<br/>            Lettura/scrittura [`IVideo`](/slides/python-net/it/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/it/aspose.slides/videoframe/trim_from_start/) | Inizio taglio [ms] |
| [`trim_from_end`](/slides/python-net/it/aspose.slides/videoframe/trim_from_end/) | Fine taglio [ms] |
| [`caption_tracks`](/slides/python-net/it/aspose.slides/videoframe/caption_tracks/) | Restituisce la collezione di sottotitoli chiusi associati al frame video.<br/>             Questa proprietà è sola lettura e restituisce un [`ICaptionsCollection`](/slides/python-net/it/aspose.slides/icaptionscollection) contenente tutte le tracce dei sottotitoli. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/videoframe/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape è usato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Salva il contenuto della Forma come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Forma come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/videoframe/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non presente e imposta le proprietà del segnaposto su quello specificato. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/videoframe/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides/videoframe/get_visual_bounds/#) | Restituisce i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [`get_geometry_paths(self)`](/slides/python-net/it/aspose.slides/videoframe/get_geometry_paths/#) | Restituisce una copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/it/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative al<br/>             angolo superiore sinistro della forma.<br/>             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/it/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Aggiorna la geometria della forma da un array di [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative al<br/>             angolo superiore sinistro della forma.<br/>             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/it/aspose.slides/videoframe/create_shape_elements/#) | Crea e restituisce un array degli elementi della forma. |

### Vedi anche
* classe [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape)
* classe [`PictureFrame`](/slides/python-net/it/aspose.slides/pictureframe)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* classe [`VideoFrame`](/slides/python-net/it/aspose.slides/videoframe)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)