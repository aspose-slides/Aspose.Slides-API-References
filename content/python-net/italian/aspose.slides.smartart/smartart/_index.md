---
title: SmartArt class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.smartart/smartart/
---
## classe SmartArt

Rappresenta un diagramma SmartArt

**Eredità:**[`SmartArt`](/slides/python-net/it/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo SmartArt espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides.smartart/smartart/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Solo lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides.smartart/smartart/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Solo lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides.smartart/smartart/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides.smartart/smartart/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides.smartart/smartart/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides.smartart/smartart/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di linea.<br/>            Solo lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides.smartart/smartart/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà degli effetti 3D per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà 3D.<br/>            Solo lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides.smartart/smartart/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di effetto.<br/>            Solo lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides.smartart/smartart/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di riempimento.<br/>            Solo lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides.smartart/smartart/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides.smartart/smartart/hyperlink_manager/) | Restituisce il gestore dei collegamenti ipertestuali.<br/>            Solo lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides.smartart/smartart/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides.smartart/smartart/z_order_position/) | Restituisce la posizione di una forma nell'ordine z.<br/>            Shapes[0] restituisce la forma più in fondo nell'ordine z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma più in avanti nell'ordine z.<br/>            Solo lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides.smartart/smartart/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Solo lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides.smartart/smartart/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno<br/>            all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo<br/>            indica rotazione in senso antiorario.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides.smartart/smartart/x/) | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides.smartart/smartart/y/) | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides.smartart/smartart/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides.smartart/smartart/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides.smartart/smartart/black_white_mode/) | La proprietà specifica come una forma verrà renderizzata in modalità di visualizzazione in bianco e nero.<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides.smartart/smartart/unique_id/) | Restituisce un identificatore interno, a livello di presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato<br/>            come una chiave unica persistente.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides.smartart/smartart/office_interop_shape_id/) | Restituisce un identificatore unico a livello di diapositiva che rimane costante per tutta la durata della forma e<br/>            consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides.smartart/smartart/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides.smartart/smartart/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides.smartart/smartart/name/) | Restituisce o imposta il nome di una forma.<br/>            Non deve essere None. Usa una stringa vuota se necessario.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides.smartart/smartart/is_decorative/) | Ottiene o imposta l'opzione 'Mark as decorative'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides.smartart/smartart/shape_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides.smartart/smartart/is_grouped/) | Determina se la forma è raggruppata.<br/>            Solo lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides.smartart/smartart/parent_group/) | Restituisce l'oggetto GroupShape padre se la forma è raggruppata. Altrimenti restituisce None.<br/>            Solo lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides.smartart/smartart/slide/) | Restituisce la diapositiva padre di una forma.<br/>            Solo lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides.smartart/smartart/presentation/) | Restituisce la presentazione padre di una diapositiva.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/it/aspose.slides.smartart/smartart/graphical_object_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/it/aspose.slides.smartart/smartart/all_nodes/) | Restituisce le collezioni di tutti i nodi nell'oggetto SmartArt.<br/>            Solo lettura [`ISmartArtNodeCollection`](/slides/python-net/it/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/it/aspose.slides.smartart/smartart/nodes/) | Restituisce le collezioni di nodi radice nell'oggetto SmartArt.<br/>            Solo lettura [`ISmartArtNodeCollection`](/slides/python-net/it/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/it/aspose.slides.smartart/smartart/layout/) | Restituisce o imposta il layout dell'oggetto SmartArt.<br/>            Lettura/scrittura [`SmartArtLayoutType`](/slides/python-net/it/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/it/aspose.slides.smartart/smartart/quick_style/) | Restituisce o imposta lo stile rapido dell'oggetto SmartArt.<br/>            Lettura/scrittura [`SmartArtQuickStyleType`](/slides/python-net/it/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/it/aspose.slides.smartart/smartart/color_style/) | Restituisce o imposta lo stile colore dell'oggetto SmartArt.<br/>            Lettura/scrittura [`SmartArtColorType`](/slides/python-net/it/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/it/aspose.slides.smartart/smartart/is_reversed/) | Restituisce o imposta lo stato del diagramma SmartArt riguardo a (da sinistra a destra) LTR o (da destra a sinistra) RTL, se il diagramma supporta l'inversione.<br/>            Lettura/scrittura **bool**. |

## Metodi

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides.smartart/smartart/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape viene usato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Salva il contenuto della Forma come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Forma come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides.smartart/smartart/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto su una specificata. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides.smartart/smartart/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides.smartart/smartart/get_visual_bounds/#) | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |

### Vedi anche
* classe [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* classe [`SmartArt`](/slides/python-net/it/aspose.slides.smartart/smartart)
* modulo [`aspose.slides.smartart`](/slides/python-net/it/aspose.slides.smartart)
* libreria [`Aspose.Slides`](/slides/python-net)