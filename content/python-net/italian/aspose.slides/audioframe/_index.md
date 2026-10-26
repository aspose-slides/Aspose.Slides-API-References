---
title: AudioFrame class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/audioframe/
---
## AudioFrame classe

Rappresenta una clip audio in una diapositiva.

**Eredità:**[`AudioFrame`](/slides/python-net/it/aspose.slides/audioframe) → [`PictureFrame`](/slides/python-net/it/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo AudioFrame espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/audioframe/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Solo lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/audioframe/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Solo lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/audioframe/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/audioframe/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/audioframe/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/audioframe/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forma che non hanno proprietà di linea.<br/>            Solo lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/audioframe/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3D per una forma.<br/>            Nota: può restituire None per alcuni tipi di forma che non hanno proprietà 3D.<br/>            Solo lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/audioframe/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forma che non hanno proprietà di effetto.<br/>            Solo lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/audioframe/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Nota: può restituire None per alcuni tipi di forma che non hanno proprietà di riempimento.<br/>            Solo lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/audioframe/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/audioframe/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/audioframe/hyperlink_manager/) | Restituisce il gestore dei collegamenti ipertestuali.<br/>            Solo lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides/audioframe/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/audioframe/z_order_position/) | Restituisce la posizione di una forma nell'ordine Z.<br/>            Shapes[0] restituisce la forma più indietro nell'ordine Z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma più in avanti nell'ordine Z.<br/>            Solo lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/audioframe/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Solo lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/audioframe/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata intorno all'asse z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo<br/>            indica rotazione in senso antiorario.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides/audioframe/x/) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/audioframe/y/) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/audioframe/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/audioframe/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/audioframe/black_white_mode/) | La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero.<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides/audioframe/unique_id/) | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato<br/>            come una chiave univoca persistente.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/audioframe/office_interop_shape_id/) | Restituisce un identificatore unico a livello di diapositiva che rimane costante per tutta la durata della forma e<br/>            permette a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides/audioframe/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/audioframe/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides/audioframe/name/) | Restituisce o imposta il nome di una forma.<br/>            Deve non essere None. Utilizzare una stringa vuota se necessario.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/audioframe/is_decorative/) | Ottiene o imposta l'opzione 'Mark as decorative'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/audioframe/shape_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IPictureFrameLock`](/slides/python-net/it/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/audioframe/is_grouped/) | Determina se la forma è raggruppata.<br/>            Solo lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides/audioframe/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Solo lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/audioframe/slide/) | Restituisce la diapositiva genitore di una forma.<br/>            Solo lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/audioframe/presentation/) | Restituisce la presentazione genitore di una diapositiva.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/it/aspose.slides/audioframe/shape_style/) | Restituisce l'oggetto stile della forma.<br/>            Solo lettura [`IShapeStyle`](/slides/python-net/it/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/it/aspose.slides/audioframe/shape_type/) | Restituisce o imposta il tipo AutoShape per un PictureFrame.<br/>            Sono consentiti tutti gli elementi del set [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype), <br/>            eccetto tutti i tipi di linee:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Lettura/scrittura [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/it/aspose.slides/audioframe/adjustments/) | Restituisce una collezione di valori di regolazione della forma.<br/>            Solo lettura [`IAdjustValueCollection`](/slides/python-net/it/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/it/aspose.slides/audioframe/picture_frame_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IPictureFrameLock`](/slides/python-net/it/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/it/aspose.slides/audioframe/picture_format/) | Restituisce l'oggetto PictureFillFormat per un picture frame.<br/>            Solo lettura [`IPictureFillFormat`](/slides/python-net/it/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/it/aspose.slides/audioframe/relative_scale_height/) | Restituisce o imposta la scala dell'altezza (relativa alle dimensioni originali dell'immagine) del picture frame. Il valore 1.0 corrisponde al 100%.<br/>            Lettura/scrittura **float**. |
| [`relative_scale_width`](/slides/python-net/it/aspose.slides/audioframe/relative_scale_width/) | Restituisce o imposta la scala della larghezza (relativa alle dimensioni originali dell'immagine) del picture frame. Il valore 1.0 corrisponde al 100%.<br/>            Lettura/scrittura **float**. |
| [`is_cameo`](/slides/python-net/it/aspose.slides/audioframe/is_cameo/) | Determina se il PictureFrame è un oggetto Cameo o meno.<br/>            Solo lettura **bool**. |
| [`audio_cd_start_track`](/slides/python-net/it/aspose.slides/audioframe/audio_cd_start_track/) | Restituisce o imposta un indice di traccia iniziale.<br/>            Lettura/scrittura **int**. |
| [`audio_cd_start_track_time`](/slides/python-net/it/aspose.slides/audioframe/audio_cd_start_track_time/) | Restituisce o imposta un tempo di traccia iniziale.<br/>            Lettura/scrittura **int**. |
| [`audio_cd_end_track`](/slides/python-net/it/aspose.slides/audioframe/audio_cd_end_track/) | Restituisce o imposta un indice di traccia finale<br/>            Lettura/scrittura **int**. |
| [`audio_cd_end_track_time`](/slides/python-net/it/aspose.slides/audioframe/audio_cd_end_track_time/) | Restituisce o imposta un tempo di traccia finale.<br/>            Lettura/scrittura **int**. |
| [`volume`](/slides/python-net/it/aspose.slides/audioframe/volume/) | Restituisce o imposta il volume audio.<br/>            Lettura/scrittura [`AudioVolumeMode`](/slides/python-net/it/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/it/aspose.slides/audioframe/play_mode/) | Restituisce o imposta la modalità di riproduzione audio.<br/>            Lettura/scrittura [`AudioPlayModePreset`](/slides/python-net/it/aspose.slides/audioplaymodepreset). |
| [`hide_at_showing`](/slides/python-net/it/aspose.slides/audioframe/hide_at_showing/) | Determina se un AudioFrame è nascosto.<br/>            Lettura/scrittura **bool**. |
| [`play_loop_mode`](/slides/python-net/it/aspose.slides/audioframe/play_loop_mode/) | Determina se un audio è ripetuto in loop.<br/>            Lettura/scrittura **bool**. |
| [`play_across_slides`](/slides/python-net/it/aspose.slides/audioframe/play_across_slides/) | Determina se l'audio è riprodotto attraverso le diapositive.<br/>             Lettura/scrittura **bool**. |
| [`rewind_audio`](/slides/python-net/it/aspose.slides/audioframe/rewind_audio/) | Determina se l'audio è automaticamente riavvolto all'inizio dopo la riproduzione.<br/>             Lettura/scrittura **bool**. |
| [`embedded`](/slides/python-net/it/aspose.slides/audioframe/embedded/) | Determina se un suono è incorporato in una presentazione.<br/>            Solo lettura **bool**. |
| [`link_path_long`](/slides/python-net/it/aspose.slides/audioframe/link_path_long/) | Restituisce o imposta il nome di un file audio collegato a un AudioFrame.<br/>            Lettura/scrittura **str**. |
| [`embedded_audio`](/slides/python-net/it/aspose.slides/audioframe/embedded_audio/) | Restituisce o imposta un oggetto audio incorporato.<br/>            Lettura/scrittura [`IAudio`](/slides/python-net/it/aspose.slides/iaudio). |
| [`fade_in_duration`](/slides/python-net/it/aspose.slides/audioframe/fade_in_duration/) | Specifica la durata temporale per la dissolvenza iniziale del media in millisecondi.<br/>             Lettura/scrittura **float**. |
| [`fade_out_duration`](/slides/python-net/it/aspose.slides/audioframe/fade_out_duration/) | Specifica la durata temporale per la dissolvenza finale del media in millisecondi.<br/>             Lettura/scrittura **float**. |
| [`volume_value`](/slides/python-net/it/aspose.slides/audioframe/volume_value/) | Restituisce o imposta il volume audio in percentuale.<br/>             Lettura/scrittura **float**. |
| [`trim_from_start`](/slides/python-net/it/aspose.slides/audioframe/trim_from_start/) | Specifica la durata temporale da rimuovere dall'inizio del media durante la riproduzione, in millisecondi.<br/>            Lettura/scrittura **float**. |
| [`trim_from_end`](/slides/python-net/it/aspose.slides/audioframe/trim_from_end/) | Specifica la durata temporale da rimuovere dalla fine del media durante la riproduzione, in millisecondi.<br/>            Lettura/scrittura **float**. |
| [`caption_tracks`](/slides/python-net/it/aspose.slides/audioframe/caption_tracks/) | Restituisce la collezione di sottotitoli chiusi associati al audio frame.<br/>            Questa proprietà è solo lettura e restituisce un [`ICaptionsCollection`](/slides/python-net/it/aspose.slides/icaptionscollection) contenente tutte le tracce di sottotitoli. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/audioframe/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape per i confini della miniatura della forma è usato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/audioframe/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/audioframe/write_as_svg/#iorawiobase) | Salva il contenuto della Forma come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/audioframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Forma come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/audioframe/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/audioframe/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non c'è e imposta le proprietà del segnaposto su uno specificato. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/audioframe/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides/audioframe/get_visual_bounds/#) | Ottiene i confini visivi della forma calcolati dal suo contenuto renderizzato. |
| [`get_geometry_paths(self)`](/slides/python-net/it/aspose.slides/audioframe/get_geometry_paths/#) | Restituisce una copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/it/aspose.slides/audioframe/set_geometry_path/#igeometrypath) | Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma.<br/>            Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/it/aspose.slides/audioframe/set_geometry_paths/#listigeometrypath) | Aggiorna la geometria della forma da un array di [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma.<br/>            Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/it/aspose.slides/audioframe/create_shape_elements/#) | Crea e restituisce un array degli elementi della forma. |

### Vedi anche
* classe [`AudioFrame`](/slides/python-net/it/aspose.slides/audioframe)
* classe [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape)
* classe [`PictureFrame`](/slides/python-net/it/aspose.slides/pictureframe)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)