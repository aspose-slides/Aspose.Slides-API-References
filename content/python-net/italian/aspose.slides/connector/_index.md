---
title: Connector class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/connector/
---
## classe Connector

Rappresenta un connettore.

**Eredità:**[`Connector`](/slides/python-net/it/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo Connector espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/connector/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Sola lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/connector/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha segnaposto.<br/>            Sola lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/connector/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/connector/raw_frame/) | Restituisce o imposta le proprietà grezze del fotogramma della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/connector/frame/) | Restituisce o imposta le proprietà del fotogramma della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/connector/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di linea.<br/>            Sola lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/connector/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà degli effetti 3D per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà 3D.<br/>            Sola lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/connector/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di effetto.<br/>            Sola lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/connector/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di riempimento.<br/>            Sola lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/connector/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/connector/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/connector/hyperlink_manager/) | Restituisce il gestore dei collegamenti ipertestuali.<br/>            Sola lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides/connector/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/connector/z_order_position/) | Restituisce la posizione di una forma nell'ordine Z.<br/>            Shapes[0] restituisce la forma in fondo all'ordine Z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma in cima all'ordine Z.<br/>            Sola lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/connector/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Sola lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/connector/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides/connector/x/) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/connector/y/) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/connector/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/connector/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/connector/black_white_mode/) | La proprietà specifica come una forma verrà renderizzata in modalità visualizzazione in bianco e nero.<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides/connector/unique_id/) | Restituisce un identificatore interno, limitato alla presentazione, destinato all'uso da componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato<br/>            come una chiave unica persistente.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/connector/office_interop_shape_id/) | Restituisce un identificatore unico limitato alla diapositiva che rimane costante per la durata della forma e<br/>            consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides/connector/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/connector/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides/connector/name/) | Restituisce o imposta il nome di una forma.<br/>            Deve non essere None. Usa una stringa vuota se necessario.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/connector/is_decorative/) | Ottiene o imposta l'opzione 'Mark as decorative'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/connector/shape_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IConnectorLock`](/slides/python-net/it/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/connector/is_grouped/) | Determina se la forma è raggruppata.<br/>            Sola lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides/connector/parent_group/) | Restituisce l'oggetto GroupShape padre se la forma è raggruppata. Altrimenti restituisce None.<br/>            Sola lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/connector/slide/) | Restituisce la diapositiva padre di una forma.<br/>            Sola lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/connector/presentation/) | Restituisce la presentazione padre di una diapositiva.<br/>            Sola lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/it/aspose.slides/connector/shape_style/) | Restituisce l'oggetto stile della forma.<br/>            Sola lettura [`IShapeStyle`](/slides/python-net/it/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/it/aspose.slides/connector/shape_type/) | Restituisce o imposta il tipo AutoShape.<br/>            Lettura/scrittura [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/it/aspose.slides/connector/adjustments/) | Restituisce una raccolta dei valori di regolazione della forma.<br/>            Sola lettura [`IAdjustValueCollection`](/slides/python-net/it/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/it/aspose.slides/connector/connector_lock/) | Restituisce i blocchi del connettore.<br/>            Sola lettura [`IConnectorLock`](/slides/python-net/it/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/it/aspose.slides/connector/start_shape_connected_to/) | Restituisce o imposta la forma a cui attaccare l'inizio del connettore.<br/>            Lettura/scrittura [`IShape`](/slides/python-net/it/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/it/aspose.slides/connector/end_shape_connected_to/) | Restituisce o imposta la forma a cui attaccare la fine del connettore.<br/>            Lettura/scrittura [`IShape`](/slides/python-net/it/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/it/aspose.slides/connector/start_shape_connection_site_index/) | Restituisce o imposta l'indice del punto di connessione per la forma di partenza.<br/>            Lettura/scrittura **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/it/aspose.slides/connector/end_shape_connection_site_index/) | Restituisce o imposta l'indice del punto di connessione per la forma finale.<br/>            Lettura/scrittura **int**. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/connector/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape è utilizzato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/connector/write_as_svg/#iorawiobase) | Salva il contenuto della Shape come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Shape come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/connector/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/connector/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non c'è e imposta le proprietà del segnaposto a una specificata. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/connector/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides/connector/get_visual_bounds/#) | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [`get_geometry_paths(self)`](/slides/python-net/it/aspose.slides/connector/get_geometry_paths/#) | Restituisce la copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/it/aspose.slides/connector/set_geometry_path/#igeometrypath) | Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo sinistro<br/>             superiore della forma.<br/>             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/it/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Aggiorna la geometria della forma da un array di [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo sinistro<br/>             superiore della forma.<br/>             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/it/aspose.slides/connector/create_shape_elements/#) | Crea e restituisce un array degli elementi della forma. |
| [`reroute(self)`](/slides/python-net/it/aspose.slides/connector/reroute/#) | Ririgira il connettore in modo che segua il percorso più breve possibile tra le forme che collega. |

### Vedi anche
* classe [`Connector`](/slides/python-net/it/aspose.slides/connector)
* classe [`GeometryShape`](/slides/python-net/it/aspose.slides/geometryshape)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)