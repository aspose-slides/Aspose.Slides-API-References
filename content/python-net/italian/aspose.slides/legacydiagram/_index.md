---
title: LegacyDiagram class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/legacydiagram/
---
## LegacyDiagram classe

Rappresenta un oggetto diagramma legacy.

**Ereditarietà:**[`LegacyDiagram`](/slides/python-net/it/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo LegacyDiagram espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/legacydiagram/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Solo lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/legacydiagram/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Solo lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/legacydiagram/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/legacydiagram/raw_frame/) | Restituisce o imposta le proprietà del frame grezzo della forma.<br/>            Lettura/Scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/legacydiagram/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/Scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/legacydiagram/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per certi tipi di forme che non hanno proprietà di linea.<br/>            Solo lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/legacydiagram/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà di effetto 3d per una forma.<br/>            Nota: può restituire None per certi tipi di forme che non hanno proprietà 3d.<br/>            Solo lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/legacydiagram/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per certi tipi di forme che non hanno proprietà di effetto.<br/>            Solo lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/legacydiagram/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Nota: può restituire None per certi tipi di forme che non hanno proprietà di riempimento.<br/>            Solo lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/legacydiagram/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse.<br/>            Lettura/Scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/Scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/legacydiagram/hyperlink_manager/) | Restituisce il gestore del collegamento ipertestuale.<br/>            Solo lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides/legacydiagram/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/Scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/legacydiagram/z_order_position/) | Restituisce la posizione di una forma nell'ordine z.<br/>            Shapes[0] restituisce la forma più in fondo all'ordine z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma più in avanti all'ordine z.<br/>            Solo lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/legacydiagram/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Solo lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/legacydiagram/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario.<br/>            Lettura/Scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides/legacydiagram/x/) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/Scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/legacydiagram/y/) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/Scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/legacydiagram/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/Scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/legacydiagram/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/Scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/legacydiagram/black_white_mode/) | La proprietà specifica come una forma verrà renderizzata in modalità bianco e nero.<br/>            Lettura/Scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides/legacydiagram/unique_id/) | Restituisce un identificatore interno, limitato alla presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato come una chiave unica persistente.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/legacydiagram/office_interop_shape_id/) | Restituisce un identificatore unico limitato alla diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento.<br/>            Solo lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides/legacydiagram/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/Scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/legacydiagram/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/Scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides/legacydiagram/name/) | Restituisce o imposta il nome di una forma.<br/>            Deve non essere None. Usa una stringa vuota se necessario.<br/>            Lettura/Scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/legacydiagram/is_decorative/) | Ottiene o imposta l'opzione 'Segna come decorativo'<br/>            Lettura/Scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/legacydiagram/shape_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/legacydiagram/is_grouped/) | Determina se la forma è raggruppata.<br/>            Solo lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides/legacydiagram/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Solo lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/legacydiagram/slide/) | Restituisce la diapositiva genitore di una forma.<br/>            Solo lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/legacydiagram/presentation/) | Restituisce la presentazione genitore di una diapositiva.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/it/aspose.slides/legacydiagram/graphical_object_lock/) | Restituisce i blocchi della forma.<br/>            Solo lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/legacydiagram/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape per i limiti della miniatura della forma è usato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | Salva il contenuto di Shape come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto di Shape come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/legacydiagram/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto su quello specificato. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/legacydiagram/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è eredidata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides/legacydiagram/get_visual_bounds/#) | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [`convert_to_smart_art(self)`](/slides/python-net/it/aspose.slides/legacydiagram/convert_to_smart_art/#) | Converte il diagramma legacy in un oggetto SmartArt modificabile. <br/>            L'oggetto SmartArt creato viene aggiunto alla forma di gruppo padre nella stessa posizione. |
| [`convert_to_group_shape(self)`](/slides/python-net/it/aspose.slides/legacydiagram/convert_to_group_shape/#) | Converte il diagramma legacy in una forma di gruppo modificabile. <br/>            L'oggetto GroupShape creato viene aggiunto alla forma di gruppo padre nella stessa posizione. |

### Vedi anche
* classe [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject)
* classe [`LegacyDiagram`](/slides/python-net/it/aspose.slides/legacydiagram)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)