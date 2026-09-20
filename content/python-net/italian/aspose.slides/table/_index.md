---
title: Table class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/table/
---
## Table classe

Rappresenta una tabella su una diapositiva.

**Eredità:**[`Table`](/slides/python-net/it/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo Table espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/table/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Sola lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides/table/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Sola lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides/table/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides/table/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides/table/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides/table/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forma che non possiedono proprietà di linea.<br/>            Sola lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides/table/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3d per una forma.<br/>            Nota: può restituire None per alcuni tipi di forma che non possiedono proprietà 3d.<br/>            Sola lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/table/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forma che non possiedono proprietà di effetto.<br/>            Sola lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/table/fill_format/) | Restituisce un oggetto TableFormat.FillFormat contenente la formattazione di riempimento per la Table.<br/>            Sola lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/table/hyperlink_click/) | Restituisce o imposta l'hyperlink definito per il clic del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/table/hyperlink_mouse_over/) | Restituisce o imposta l'hyperlink definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/table/hyperlink_manager/) | Restituisce il gestore degli hyperlink.<br/>            Sola lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides/table/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides/table/z_order_position/) | Restituisce la posizione di una forma nell'ordine Z.<br/>            Shapes[0] restituisce la forma più in fondo all'ordine Z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma più in primo piano nell'ordine Z.<br/>            Sola lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/table/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Sola lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides/table/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario.<br/>            Lettura/scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides/table/x/) | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides/table/y/) | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides/table/width/) | Ottiene o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/table/height/) | Ottiene o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/table/black_white_mode/) | La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero.<br/>            Lettura/scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides/table/unique_id/) | Restituisce un identificatore interno, limitato alla presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato<br/>            come una chiave univoca persistente.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/table/office_interop_shape_id/) | Restituisce un identificatore univoco limitato alla diapositiva che rimane costante per la durata della forma e<br/>            consente a PowerPoint o al codice interop di riferirsi in modo affidabile alla forma da qualsiasi punto del documento.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides/table/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/table/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides/table/name/) | Restituisce o imposta il nome di una forma.<br/>            Deve non essere None. Usa una stringa vuota se necessario.<br/>            Lettura/scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides/table/is_decorative/) | Ottiene o imposta l'opzione 'Mark as decorative'<br/>            Lettura/scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides/table/shape_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides/table/is_grouped/) | Determina se la forma è raggruppata.<br/>            Sola lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides/table/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Sola lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides/table/slide/) | Restituisce la diapositiva genitore di una forma.<br/>            Sola lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/table/presentation/) | Restituisce la presentazione genitore di una diapositiva.<br/>            Sola lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/it/aspose.slides/table/graphical_object_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/it/aspose.slides/table/rows/) | Restituisce la raccolta di righe.<br/>            Sola lettura [`IRowCollection`](/slides/python-net/it/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/it/aspose.slides/table/columns/) | Restituisce la raccolta di colonne.<br/>            Sola lettura [`IColumnCollection`](/slides/python-net/it/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/it/aspose.slides/table/table_format/) | Restituisce l'oggetto TableFormat che contiene le proprietà di formattazione per questa tabella.<br/>            Sola lettura [`ITableFormat`](/slides/python-net/it/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/it/aspose.slides/table/style_preset/) | Ottiene o imposta lo stile di tabella incorporato.<br/>            Lettura/scrittura [`TableStylePreset`](/slides/python-net/it/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/it/aspose.slides/table/right_to_left/) | Determina se la tabella ha ordine di lettura da destra a sinistra.<br/>            Lettura/scrittura **bool**. |
| [`first_row`](/slides/python-net/it/aspose.slides/table/first_row/) | Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale.<br/>            Lettura/scrittura **bool**. |
| [`first_col`](/slides/python-net/it/aspose.slides/table/first_col/) | Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale.<br/>            Lettura/scrittura **bool**. |
| [`last_row`](/slides/python-net/it/aspose.slides/table/last_row/) | Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale.<br/>            Lettura/scrittura **bool**. |
| [`last_col`](/slides/python-net/it/aspose.slides/table/last_col/) | Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale.<br/>            Lettura/scrittura **bool**. |
| [`horizontal_banding`](/slides/python-net/it/aspose.slides/table/horizontal_banding/) | Determina se le righe pari devono essere disegnate con una formattazione diversa.<br/>            Lettura/scrittura **bool**. |
| [`vertical_banding`](/slides/python-net/it/aspose.slides/table/vertical_banding/) | Determina se le colonne pari devono essere disegnate con una formattazione diversa.<br/>            Lettura/scrittura **bool**. |

## Metodi

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/table/get_image/#) | Restituisce la miniatura della forma.<br/>            ShapeThumbnailBounds.Shape è il tipo di bordo della miniatura della forma usato per impostazione predefinita. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/table/write_as_svg/#iorawiobase) | Salva il contenuto della Shape come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Shape come file SVG. |
| [`set_text_format(self, source)`](/slides/python-net/it/aspose.slides/table/set_text_format/#iportionformat) | Imposta le proprietà di formattazione della porzione definita a tutte le porzioni delle celle della tabella. |
| [`set_text_format(self, source)`](/slides/python-net/it/aspose.slides/table/set_text_format/#iparagraphformat) | Imposta le proprietà di formattazione del paragrafo definito a tutti i paragrafi delle celle della tabella. |
| [`set_text_format(self, source)`](/slides/python-net/it/aspose.slides/table/set_text_format/#itextframeformat) | Imposta le proprietà di formattazione del frame di testo definito a tutti i frame di testo delle celle della tabella. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/table/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/table/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto a quello specificato. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/table/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma proveniente dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides/table/get_visual_bounds/#) | Ottiene i confini visivi della forma calcolati dal suo contenuto renderizzato. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/it/aspose.slides/table/merge_cells/#icell-icell-bool) | Unisce le celle adiacenti. |

### Vedi anche
* class [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject)
* class [`Shape`](/slides/python-net/it/aspose.slides/shape)
* class [`Table`](/slides/python-net/it/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)