---
title: ZoomObject class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/zoomobject/
---
## ZoomObject classe

Rappresenta un oggetto Zoom in una diapositiva.

**Eredità:**[`ZoomObject`](/slides/python-net/it/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo ZoomObject espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/zoomobject/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Solo lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/zoomobject/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Solo lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/zoomobject/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/zoomobject/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/zoomobject/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/zoomobject/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di linea.<br/>            Solo lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/zoomobject/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà degli effetti 3D per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà 3D.<br/>            Solo lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/zoomobject/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di effetto.<br/>            Solo lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/zoomobject/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di riempimento.<br/>            Solo lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/zoomobject/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/zoomobject/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/zoomobject/hyperlink_manager/) | Restituisce il gestore dei collegamenti ipertestuali.<br/>            Solo lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides/zoomobject/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/zoomobject/z_order_position/) | Restituisce la posizione di una forma nell'ordine Z.<br/>            Shapes[0] restituisce la forma più in fondo dell'ordine Z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma più in alto dell'ordine Z.<br/>            Solo lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/zoomobject/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Solo lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/zoomobject/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo<br/>            indica rotazione in senso antiorario.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides/zoomobject/x/) | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/zoomobject/y/) | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/zoomobject/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/zoomobject/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/zoomobject/black_white_mode/) | La proprietà specifica come una forma verrà resa nella modalità di visualizzazione in bianco e nero.<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides/zoomobject/unique_id/) | Restituisce un identificatore interno, limitato alla presentazione, destinato all'uso da componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato<br/>            una chiave univoca persistente.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/zoomobject/office_interop_shape_id/) | Restituisce un identificatore univoco limitato alla diapositiva che rimane costante per la durata della forma e<br/>            consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides/zoomobject/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/zoomobject/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides/zoomobject/name/) | Restituisce o imposta il nome di una forma.<br/>            Non deve essere None. Utilizzare una stringa vuota se necessario.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/zoomobject/is_decorative/) | Ottiene o imposta l'opzione 'Mark as decorative'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/zoomobject/shape_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/zoomobject/is_grouped/) | Determina se la forma è raggruppata.<br/>            Solo lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides/zoomobject/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Solo lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/zoomobject/slide/) | Restituisce la diapositiva genitore di una forma.<br/>            Solo lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/zoomobject/presentation/) | Restituisce la presentazione genitore di una diapositiva.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/it/aspose.slides/zoomobject/graphical_object_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/it/aspose.slides/zoomobject/image_type/) | Ottiene o imposta il tipo di immagine di un oggetto zoom.<br/>            Lettura/scrittura [`ZoomImageType`](/slides/python-net/it/aspose.slides/zoomimagetype).<br/>            Valore predefinito: Preview |
| [`return_to_parent`](/slides/python-net/it/aspose.slides/zoomobject/return_to_parent/) | Ottiene o imposta il comportamento di navigazione nella presentazione.<br/>            Lettura/scrittura **bool**.<br/>            Valore predefinito: false |
| [`show_background`](/slides/python-net/it/aspose.slides/zoomobject/show_background/) | Ottiene o imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione.<br/>            Lettura/scrittura **bool**.<br/>            Valore predefinito: true |
| [`zoom_image`](/slides/python-net/it/aspose.slides/zoomobject/zoom_image/) | Ottiene o imposta l'immagine per l'oggetto zoom.<br/>            Lettura/scrittura [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/it/aspose.slides/zoomobject/transition_duration/) | Ottiene o imposta la durata della transizione tra Zoom e diapositiva.<br/>            Lettura/scrittura **float**.<br/>            Valore predefinito: 1.0f |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/zoomobject/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape dei confini della miniatura della forma è usato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Salva il contenuto della Shape come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Shape come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/zoomobject/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non presente e imposta le proprietà del segnaposto su uno specificato. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/zoomobject/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides/zoomobject/get_visual_bounds/#) | Ottiene i confini visivi della forma calcolati dal suo contenuto renderizzato. |

### Vedi anche
* classe [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* classe [`ZoomObject`](/slides/python-net/it/aspose.slides/zoomobject)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)