---
title: GeometryShape class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/geometryshape/
---
## GeometryShape classe

Rappresenta la classe base per tutte le forme geometriche.

**Ereditarietà:**[`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo GeometryShape espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/geometryshape/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/geometryshape/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Read-only [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/geometryshape/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Read-only [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/geometryshape/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Read/write [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/geometryshape/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Read/write [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/geometryshape/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Note: può restituire None per alcuni tipi di forme che non hanno proprietà di linea.<br/>            Read-only [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/geometryshape/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3D per una forma.<br/>            Note: può restituire None per alcuni tipi di forme che non hanno proprietà 3D.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/geometryshape/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Note: può restituire None per alcuni tipi di forme che non hanno proprietà di effetto.<br/>            Read-only [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/geometryshape/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Note: può restituire None per alcuni tipi di forme che non hanno proprietà di riempimento.<br/>            Read-only [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/geometryshape/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse.<br/>            Read/write [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/geometryshape/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Read/write [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/geometryshape/hyperlink_manager/) | Restituisce il gestore dei collegamenti ipertestuali.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides/geometryshape/hidden/) | Determina se la forma è nascosta.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/geometryshape/z_order_position/) | Restituisce la posizione di una forma nell'ordine Z.<br/>            Shapes[0] restituisce la forma più arretrata nell'ordine Z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma più avanzata nell'ordine Z.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/geometryshape/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/geometryshape/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo<br/>            indica rotazione in senso antiorario.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/it/aspose.slides/geometryshape/x/) | Recupera o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/it/aspose.slides/geometryshape/y/) | Recupera o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/it/aspose.slides/geometryshape/width/) | Recupera o imposta la larghezza della forma, misurata in punti.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/it/aspose.slides/geometryshape/height/) | Recupera o imposta l'altezza della forma, misurata in punti.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/geometryshape/black_white_mode/) | La proprietà specifica come una forma verrà renderizzata in modalità bianco-nero.<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides/geometryshape/unique_id/) | Restituisce un identificatore interno, limitato alla presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato<br/>            come una chiave unica persistente.<br/>            Read-only **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/geometryshape/office_interop_shape_id/) | Restituisce un identificatore unico limitato alla diapositiva che rimane costante per la durata della forma e<br/>            consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento.<br/>            Read-only **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides/geometryshape/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/geometryshape/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/it/aspose.slides/geometryshape/name/) | Restituisce o imposta il nome di una forma.<br/>            Deve non essere None. Usa una stringa vuota se necessario.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/geometryshape/is_decorative/) | Recupera o imposta l'opzione 'Mark as decorative'.<br/>            Read/write **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/geometryshape/shape_lock/) | Restituisce i blocchi della forma.<br/>            Read-only [`IBaseShapeLock`](/slides/python-net/it/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/geometryshape/is_grouped/) | Determina se la forma è raggruppata.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides/geometryshape/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Read-only [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/geometryshape/slide/) | Restituisce la diapositiva genitore di una forma.<br/>            Read-only [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/geometryshape/presentation/) | Restituisce la presentazione genitore di una diapositiva.<br/>            Read-only [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/it/aspose.slides/geometryshape/shape_style/) | Restituisce l'oggetto stile della forma.<br/>            Read-only [`IShapeStyle`](/slides/python-net/it/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type/) | Restituisce o imposta il tipo predefinito di geometria.<br/>            Nota: al cambiamento del valore tutti i valori di regolazione verranno ripristinati ai valori predefiniti.<br/>            Read/write [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/it/aspose.slides/geometryshape/adjustments/) | Restituisce una collezione dei valori di regolazione della forma.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/it/aspose.slides/iadjustvaluecollection). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/geometryshape/get_image/#) | Restituisce l'anteprima della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape per i limiti dell'anteprima della forma è usato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/geometryshape/get_image/#shapethumbnailbounds-float-float) | Restituisce l'anteprima della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/geometryshape/write_as_svg/#iorawiobase) | Salva il contenuto della Forma come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/geometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Forma come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/geometryshape/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/geometryshape/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non ce ne è e imposta le proprietà del segnaposto a quello specificato. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/geometryshape/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides/geometryshape/get_visual_bounds/#) | Recupera i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [`get_geometry_paths(self)`](/slides/python-net/it/aspose.slides/geometryshape/get_geometry_paths/#) | Restituisce la copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/it/aspose.slides/geometryshape/set_geometry_path/#igeometrypath) | Aggiorna la geometria della forma dal oggetto [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative al lato sinistro<br/>             angolo superiore della forma.<br/>             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/it/aspose.slides/geometryshape/set_geometry_paths/#listigeometrypath) | Aggiorna la geometria della forma da un array di [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative al lato sinistro<br/>             angolo superiore della forma.<br/>             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/it/aspose.slides/geometryshape/create_shape_elements/#) | Crea e restituisce un array degli elementi della forma. |

### Vedi anche
* classe [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)