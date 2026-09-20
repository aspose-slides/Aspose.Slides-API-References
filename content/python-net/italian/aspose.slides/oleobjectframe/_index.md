---
title: OleObjectFrame class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/oleobjectframe/
---
## OleObjectFrame classe

**Eredità:**[`OleObjectFrame`](/slides/python-net/it/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo OleObjectFrame espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/oleobjectframe/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Sola lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/oleobjectframe/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha alcun segnaposto.<br/>            Sola lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/oleobjectframe/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/oleobjectframe/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/oleobjectframe/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/oleobjectframe/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di linea.<br/>            Sola lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/oleobjectframe/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3D per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà 3D.<br/>            Sola lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/oleobjectframe/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di effetto.<br/>            Sola lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/oleobjectframe/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di riempimento.<br/>            Sola lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/oleobjectframe/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il click del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/oleobjectframe/hyperlink_manager/) | Restituisce il gestore dei collegamenti ipertestuali.<br/>            Sola lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides/oleobjectframe/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/oleobjectframe/z_order_position/) | Restituisce la posizione di una forma nell'ordine z.<br/>            Shapes[0] restituisce la forma più in fondo nell'ordine z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma più in evidenza nell'ordine z.<br/>            Sola lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/oleobjectframe/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Sola lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/oleobjectframe/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z.<br/>            Un valore positivo indica rotazione oraria; un valore negativo indica rotazione antioraria.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides/oleobjectframe/x/) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/oleobjectframe/y/) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/oleobjectframe/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/oleobjectframe/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/oleobjectframe/black_white_mode/) | La proprietà specifica come una forma verrà visualizzata in modalità bianco-nero.<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides/oleobjectframe/unique_id/) | Restituisce un identificatore interno, limitato alla presentazione, destinato all'uso da componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato<br/>            come una chiave unica persistente.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/oleobjectframe/office_interop_shape_id/) | Restituisce un identificatore unico limitato alla diapositiva che rimane costante per la durata della forma e<br/>            consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides/oleobjectframe/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/oleobjectframe/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides/oleobjectframe/name/) | Restituisce o imposta il nome di una forma.<br/>            Non deve essere None. Utilizzare una stringa vuota se necessario.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/oleobjectframe/is_decorative/) | Ottiene o imposta l'opzione 'Segna come decorativa'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/oleobjectframe/shape_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/oleobjectframe/is_grouped/) | Determina se la forma è raggruppata.<br/>            Sola lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides/oleobjectframe/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Sola lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/oleobjectframe/slide/) | Restituisce la diapositiva genitore di una forma.<br/>            Sola lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/oleobjectframe/presentation/) | Restituisce la presentazione genitore di una diapositiva.<br/>            Sola lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/it/aspose.slides/oleobjectframe/graphical_object_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/it/aspose.slides/oleobjectframe/substitute_picture_format/) | Restituisce l'oggetto delle proprietà di riempimento immagine OleObject.<br/>            Sola lettura [`IPictureFillFormat`](/slides/python-net/it/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/it/aspose.slides/oleobjectframe/substitute_picture_title/) | Restituisce o imposta il titolo per l'icona OleObject.<br/>            Lettura/scrittura **str**. |
| [`object_name`](/slides/python-net/it/aspose.slides/oleobjectframe/object_name/) | Restituisce o imposta il nome di un oggetto.<br/>            Lettura/scrittura **str**. |
| [`object_prog_id`](/slides/python-net/it/aspose.slides/oleobjectframe/object_prog_id/) | Restituisce il ProgID di un oggetto.<br/>            Sola lettura **str**. |
| [`link_file_name`](/slides/python-net/it/aspose.slides/oleobjectframe/link_file_name/) | Restituisce il percorso completo a un file collegato. Verrà utilizzato il nome file breve.<br/>            Sola lettura **str**. |
| [`link_path_long`](/slides/python-net/it/aspose.slides/oleobjectframe/link_path_long/) | Restituisce il percorso completo a un file collegato. Verrà utilizzato il nome file lungo.<br/>            Lettura/scrittura **str**. |
| [`link_path_relative`](/slides/python-net/it/aspose.slides/oleobjectframe/link_path_relative/) | Restituisce il percorso relativo a un file collegato se presente, altrimenti restituisce una stringa vuota.<br/>             Sola lettura **str**. |
| [`embedded_file_label`](/slides/python-net/it/aspose.slides/oleobjectframe/embedded_file_label/) | Restituisce il nome file dell'oggetto OLE incorporato |
| [`embedded_file_name`](/slides/python-net/it/aspose.slides/oleobjectframe/embedded_file_name/) | Restituisce il percorso dell'oggetto OLE incorporato |
| [`embedded_data`](/slides/python-net/it/aspose.slides/oleobjectframe/embedded_data/) | Ottiene o imposta le informazioni sui dati OLE incorporati.<br/>            Lettura/scrittura [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/it/aspose.slides/oleobjectframe/is_object_icon/) | Determina se un oggetto è visibile come icona.<br/>            Lettura/scrittura **bool**. |
| [`is_object_link`](/slides/python-net/it/aspose.slides/oleobjectframe/is_object_link/) | Determina se un oggetto è collegato a un file esterno.<br/>            Sola lettura **bool**. |
| [`update_automatic`](/slides/python-net/it/aspose.slides/oleobjectframe/update_automatic/) | Determina se l'oggetto incorporato collegato viene aggiornato automaticamente quando la presentazione è aperta o stampata.<br/>            Lettura/scrittura **bool**. |

## Metodi

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/oleobjectframe/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape viene utilizzato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Salva il contenuto della Forma come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Forma come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/oleobjectframe/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non ce ne è e imposta le proprietà del segnaposto a quello specificato. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/oleobjectframe/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o diapositiva master da cui la forma corrente è ereditata).<br/>            Restituisce None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides/oleobjectframe/get_visual_bounds/#) | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/it/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Imposta le informazioni sui dati OLE incorporati.<br/>            <br/>            Questo metodo modifica le proprietà dell'oggetto per riflettere i nuovi dati e <br/>            imposta il flag IsObjectLink a false, indicando che l'oggetto OLE è incorporato. |

### Vedi anche
* classe [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject)
* classe [`OleObjectFrame`](/slides/python-net/it/aspose.slides/oleobjectframe)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)