---
title: AutoShape class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/autoshape/
---
## AutoShape classe

**Ereditarietà:**[`AutoShape`](/slides/python-net/it/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo AutoShape espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/autoshape/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Solo lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/autoshape/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Solo lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/autoshape/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/autoshape/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/autoshape/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/autoshape/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di linea.<br/>            Solo lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/autoshape/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà di effetto 3d per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà 3d.<br/>            Solo lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/autoshape/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di effetto.<br/>            Solo lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/autoshape/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di riempimento.<br/>            Solo lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/autoshape/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il click del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/autoshape/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/autoshape/hyperlink_manager/) | Restituisce il gestore dei collegamenti ipertestuali.<br/>            Solo lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides/autoshape/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/autoshape/z_order_position/) | Restituisce la posizione di una forma nell'ordine Z.<br/>            Shapes[0] restituisce la forma più arretrata nell'ordine Z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma più anteriore nell'ordine Z.<br/>            Solo lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/autoshape/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Solo lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/autoshape/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides/autoshape/x/) | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/autoshape/y/) | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/autoshape/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/autoshape/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/autoshape/black_white_mode/) | La proprietà specifica come una forma verrà renderizzata in modalità visualizzazione in bianco e nero.<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides/autoshape/unique_id/) | Restituisce un identificatore interno, limitato alla presentazione, destinato all'uso da parte di add-in o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato<br/>            una chiave unica persistente.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/autoshape/office_interop_shape_id/) | Restituisce un identificatore unico limitato alla diapositiva che rimane costante per tutta la vita della forma e<br/>            consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides/autoshape/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/autoshape/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides/autoshape/name/) | Restituisce o imposta il nome di una forma.<br/>            Non deve essere None. Utilizzare una stringa vuota se necessario.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/autoshape/is_decorative/) | Ottiene o imposta l'opzione 'Segna come decorativo'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/autoshape/shape_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IAutoShapeLock`](/slides/python-net/it/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/autoshape/is_grouped/) | Determina se la forma è raggruppata.<br/>            Solo lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides/autoshape/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Solo lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/autoshape/slide/) | Restituisce la diapositiva genitore di una forma.<br/>            Solo lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/autoshape/presentation/) | Restituisce la presentazione genitore di una diapositiva.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/it/aspose.slides/autoshape/shape_style/) | Restituisce l'oggetto stile della forma.<br/>            Solo lettura [`IShapeStyle`](/slides/python-net/it/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/it/aspose.slides/autoshape/shape_type/) | Restituisce o imposta il tipo predefinito di geometria.<br/>            Nota: al cambiamento del valore tutti i valori di aggiustamento saranno ripristinati ai valori predefiniti.<br/>            Lettura/scrittura [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/it/aspose.slides/autoshape/adjustments/) | Restituisce una collezione dei valori di aggiustamento della forma.<br/>            Solo lettura [`IAdjustValueCollection`](/slides/python-net/it/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/it/aspose.slides/autoshape/auto_shape_lock/) | Restituisce i blocchi dell'autoshape.<br/>            Solo lettura [`IAutoShapeLock`](/slides/python-net/it/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/it/aspose.slides/autoshape/text_frame/) | Restituisce l'oggetto TextFrame per l'AutoShape.<br/>            Solo lettura [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/it/aspose.slides/autoshape/use_background_fill/) | Determina se questo autoshape dovrebbe essere riempito con lo sfondo della diapositiva invece che specificato dallo stile o dal formato di riempimento.<br/>            Lettura/scrittura **bool**. |
| [`is_text_box`](/slides/python-net/it/aspose.slides/autoshape/is_text_box/) | Specifica se la forma è una casella di testo. |

## Metodi

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/autoshape/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape per i limiti della miniatura della forma è usato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Salva il contenuto della Forma come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Forma come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/autoshape/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto a quelle specificate. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/autoshape/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides/autoshape/get_visual_bounds/#) | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [`get_geometry_paths(self)`](/slides/python-net/it/aspose.slides/autoshape/get_geometry_paths/#) | Restituisce una copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/it/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma.<br/>             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/it/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Aggiorna la geometria della forma da un array di [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma.<br/>             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/it/aspose.slides/autoshape/create_shape_elements/#) | Crea e restituisce un array degli elementi della forma. |
| [`add_text_frame(self, text)`](/slides/python-net/it/aspose.slides/autoshape/add_text_frame/#str) | Aggiunge un nuovo TextFrame a una forma.<br/>            Se la forma ha già un TextFrame, cambia semplicemente il suo testo. |

### Vedi anche
* class [`AutoShape`](/slides/python-net/it/aspose.slides/autoshape)
* class [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape)
* class [`Shape`](/slides/python-net/it/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)