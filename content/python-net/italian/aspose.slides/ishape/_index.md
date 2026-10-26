---
title: IShape class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishape/
---
## IShape classe

Rappresenta una forma su una diapositiva.

Il tipo IShape espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/ishape/is_text_holder/) | Determina se la forma è TextHolder.<br/>            Solo lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/ishape/placeholder/) | Restituisce il segnaposto per una forma.<br/>            Solo lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/ishape/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/ishape/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/ishape/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/ishape/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Solo lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/ishape/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Solo lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/ishape/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Solo lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/ishape/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Solo lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/it/aspose.slides/ishape/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/ishape/z_order_position/) | Restituisce la posizione di una forma nell'ordine Z.<br/>            Shapes[0] restituisce la forma posta in fondo all'ordine Z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma posta in primo piano nell'ordine Z.<br/>            Solo lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/ishape/connection_site_count/) | Restituisce il numero di punti di collegamento sulla forma.<br/>            Solo lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/ishape/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides/ishape/x/) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/ishape/y/) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/ishape/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/ishape/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`alternative_text`](/slides/python-net/it/aspose.slides/ishape/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/ishape/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides/ishape/name/) | Restituisce o imposta il nome di una forma.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/ishape/is_decorative/) | Ottiene o imposta l'opzione 'Segna come decorativa'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/ishape/shape_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IBaseShapeLock`](/slides/python-net/it/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/it/aspose.slides/ishape/unique_id/) | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato<br/>            come una chiave unica persistente.<br/>            Solo lettura **int**.<br/>            Vedi anche [`IShape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/ishape/office_interop_shape_id/) | Restituisce un identificatore unico a livello di diapositiva che rimane costante per tutta la durata della forma e<br/>            consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento.<br/>            Solo lettura **int**.<br/>            Vedi anche [`IShape.unique_id`](/slides/python-net/it/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/ishape/is_grouped/) | Determina se la forma è raggruppata.<br/>            Solo lettura **bool**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/ishape/black_white_mode/) | La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero.<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/it/aspose.slides/ishape/parent_group/) | Restituisce l'oggetto GroupShape padre se la forma è raggruppata. Altrimenti restituisce None.<br/>            Solo lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/ishape/hyperlink_manager/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/ishape/get_image/#) | Restituisce la miniatura della forma.<br/>            È usato per impostazione predefinita il tipo ShapeThumbnailBounds.Shape per i limiti della miniatura della forma. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/ishape/write_as_svg/#iorawiobase) | Salva il contenuto della Forma come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Forma come file SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/ishape/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non presente e imposta le proprietà del segnaposto su quello specificato. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/ishape/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/ishape/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma proveniente dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)