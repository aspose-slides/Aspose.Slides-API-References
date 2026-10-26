---
title: Chart class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chart/
---
## Chart classe

Rappresenta un grafico Chart su una slide.

**Eredità:**[`Chart`](/slides/python-net/it/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/it/aspose.slides/shape)

Il tipo Chart espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`is_text_holder`](/slides/python-net/it/aspose.slides.charts/chart/is_text_holder/) | Determina se la forma è TextHolder_PPT.<br/>            Sola lettura **bool**. |
| [`placeholder`](/slides/python-net/it/aspose.slides.charts/chart/placeholder/) | Restituisce il segnaposto per una forma. Restituisce None se la forma non ha un segnaposto.<br/>            Sola lettura [`IPlaceholder`](/slides/python-net/it/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/it/aspose.slides.charts/chart/custom_data/) | Restituisce i dati personalizzati della forma.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/it/aspose.slides.charts/chart/raw_frame/) | Restituisce o imposta le proprietà grezze del frame della forma.<br/>            Lettura/Scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/it/aspose.slides.charts/chart/frame/) | Restituisce o imposta le proprietà del frame della forma.<br/>            Lettura/Scrittura [`IShapeFrame`](/slides/python-net/it/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/it/aspose.slides.charts/chart/line_format/) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di linea.<br/>            Sola lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/it/aspose.slides.charts/chart/three_d_format/) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3D per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà 3D.<br/>            Sola lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides.charts/chart/effect_format/) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di effetto.<br/>            Sola lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides.charts/chart/fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma.<br/>            Nota: può restituire None per alcuni tipi di forme che non hanno proprietà di riempimento.<br/>            Sola lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides.charts/chart/hyperlink_click/) | Restituisce o imposta l'hyperlink definito per il clic del mouse.<br/>            Lettura/Scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides.charts/chart/hyperlink_mouse_over/) | Restituisce o imposta l'hyperlink definito per il passaggio del mouse.<br/>            Lettura/Scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides.charts/chart/hyperlink_manager/) | Restituisce il gestore degli hyperlink.<br/>            Sola lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/it/aspose.slides.charts/chart/hidden/) | Determina se la forma è nascosta.<br/>            Lettura/Scrittura **bool**. |
| [`z_order_position`](/slides/python-net/it/aspose.slides.charts/chart/z_order_position/) | Restituisce la posizione di una forma nell'ordine z.<br/>            Shapes[0] restituisce la forma posta in fondo all'ordine z,<br/>            e Shapes[Shapes.Count - 1] restituisce la forma posta in prima posizione nell'ordine z.<br/>            Sola lettura **int**. |
| [`connection_site_count`](/slides/python-net/it/aspose.slides.charts/chart/connection_site_count/) | Restituisce il numero di punti di connessione sulla forma.<br/>            Sola lettura **int**. |
| [`rotation`](/slides/python-net/it/aspose.slides.charts/chart/rotation/) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z.<br/>            Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario.<br/>            Lettura/Scrittura **float**. |
| [`x`](/slides/python-net/it/aspose.slides.charts/chart/x/) | Restituisce o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/Scrittura **float**. |
| [`y`](/slides/python-net/it/aspose.slides.charts/chart/y/) | Restituisce o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti.<br/>            Lettura/Scrittura **float**. |
| [`width`](/slides/python-net/it/aspose.slides.charts/chart/width/) | Restituisce o imposta la larghezza della forma, misurata in punti.<br/>            Lettura/Scrittura **float**. |
| [`height`](/slides/python-net/it/aspose.slides.charts/chart/height/) | Restituisce o imposta l'altezza della forma, misurata in punti.<br/>            Lettura/Scrittura **float**. |
| [`black_white_mode`](/slides/python-net/it/aspose.slides.charts/chart/black_white_mode/) | La proprietà specifica come una forma verrà renderizzata in modalità bianco e nero.<br/>            Lettura/Scrittura [`BlackWhiteMode`](/slides/python-net/it/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/it/aspose.slides.charts/chart/unique_id/) | Restituisce un identificatore interno, limitato alla presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice.<br/>            Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato<br/>            come una chiave univoca persistente.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.office_interop_shape_id`](/slides/python-net/it/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides.charts/chart/office_interop_shape_id/) | Restituisce un identificatore unico limitato alla slide che rimane costante per la durata della forma e<br/>            consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento.<br/>            Sola lettura **int**.<br/>            Vedi anche [`Shape.unique_id`](/slides/python-net/it/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/it/aspose.slides.charts/chart/alternative_text/) | Restituisce o imposta il testo alternativo associato a una forma.<br/>            Lettura/Scrittura **str**. |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides.charts/chart/alternative_text_title/) | Restituisce o imposta il titolo del testo alternativo associato a una forma.<br/>            Lettura/Scrittura **str**. |
| [`name`](/slides/python-net/it/aspose.slides.charts/chart/name/) | Restituisce o imposta il nome di una forma.<br/>            Non deve essere None. Usa una stringa vuota se necessario.<br/>            Lettura/Scrittura **str**. |
| [`is_decorative`](/slides/python-net/it/aspose.slides.charts/chart/is_decorative/) | Restituisce o imposta l'opzione 'Mark as decorative'<br/>            Lettura/Scrittura **bool**. |
| [`shape_lock`](/slides/python-net/it/aspose.slides.charts/chart/shape_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/it/aspose.slides.charts/chart/is_grouped/) | Determina se la forma è raggruppata.<br/>            Sola lettura **bool**. |
| [`parent_group`](/slides/python-net/it/aspose.slides.charts/chart/parent_group/) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce None.<br/>            Sola lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/it/aspose.slides.charts/chart/slide/) | Restituisce la slide genitore di una forma.<br/>            Sola lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides.charts/chart/presentation/) | Restituisce la presentazione genitore di una slide.<br/>            Sola lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/it/aspose.slides.charts/chart/graphical_object_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IGraphicalObjectLock`](/slides/python-net/it/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/it/aspose.slides.charts/chart/plot_visible_cells_only/) | Determina se vengono tracciate solo le celle visibili. False per tracciare sia le celle visibili sia quelle nascoste.<br/>            Lettura/Scrittura **bool**. |
| [`display_blanks_as`](/slides/python-net/it/aspose.slides.charts/chart/display_blanks_as/) | Restituisce o imposta il modo di tracciare le celle vuote in un grafico Chart.<br/>            Lettura/Scrittura [`DisplayBlanksAsType`](/slides/python-net/it/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/it/aspose.slides.charts/chart/chart_data/) | Restituisce informazioni sui dati collegati o incorporati associati a un grafico Chart.<br/>            Sola lettura [`IChartData`](/slides/python-net/it/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/it/aspose.slides.charts/chart/has_title/) | Determina se un grafico Chart ha un titolo visibile.<br/>            Lettura/Scrittura **bool**. |
| [`chart_title`](/slides/python-net/it/aspose.slides.charts/chart/chart_title/) | Restituisce o imposta il titolo del grafico Chart.<br/>            Sola lettura [`IChartTitle`](/slides/python-net/it/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/it/aspose.slides.charts/chart/has_data_table/) | Determina se un grafico Chart ha una tabella dati.<br/>            Lettura/Scrittura **bool**. |
| [`has_legend`](/slides/python-net/it/aspose.slides.charts/chart/has_legend/) | Determina se un grafico Chart ha una legenda.<br/>            Lettura/Scrittura **bool**. |
| [`legend`](/slides/python-net/it/aspose.slides.charts/chart/legend/) | Restituisce o imposta una legenda per un grafico Chart.<br/>            Sola lettura [`ILegend`](/slides/python-net/it/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/it/aspose.slides.charts/chart/chart_data_table/) | Restituisce una tabella dati di un grafico Chart.<br/>            Sola lettura [`IDataTable`](/slides/python-net/it/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/it/aspose.slides.charts/chart/style/) | Restituisce o imposta lo stile del grafico Chart.<br/>            Lettura/Scrittura [`StyleType`](/slides/python-net/it/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/it/aspose.slides.charts/chart/type/) | Restituisce o imposta il tipo di grafico Chart.<br/>            Lettura/Scrittura [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/it/aspose.slides.charts/chart/plot_area/) | Rappresenta l'area di disegno di un grafico Chart.<br/>            Sola lettura [`IChartPlotArea`](/slides/python-net/it/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/it/aspose.slides.charts/chart/rotation_3d/) | Restituisce una rotazione 3D di un grafico Chart.<br/>            Sola lettura [`IRotation3D`](/slides/python-net/it/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/it/aspose.slides.charts/chart/back_wall/) | Restituisce un oggetto che consente di modificare il formato della parete posteriore di un grafico Chart 3D.<br/>            Sola lettura [`IChartWall`](/slides/python-net/it/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/it/aspose.slides.charts/chart/side_wall/) | Restituisce un oggetto che consente di modificare il formato della parete laterale di un grafico Chart 3D.<br/>            Sola lettura [`IChartWall`](/slides/python-net/it/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/it/aspose.slides.charts/chart/floor/) | Restituisce un oggetto che consente di modificare il formato del pavimento di un grafico Chart 3D.<br/>            Sola lettura [`IChartWall`](/slides/python-net/it/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/it/aspose.slides.charts/chart/text_format/) | Restituisce il formato del testo del grafico.<br/>            La proprietà non è applicabile per i seguenti tipi: [`ChartType.TREEMAP`](/slides/python-net/it/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/it/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/it/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/it/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/it/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/it/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Sola lettura [`IChartTextFormat`](/slides/python-net/it/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/it/aspose.slides.charts/chart/theme_manager/) | Restituisce il gestore del tema.<br/>            Sola lettura [`IOverrideThemeManager`](/slides/python-net/it/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/it/aspose.slides.charts/chart/user_shapes/) | Specifica le forme disegnate sopra il grafico Chart.<br/>            Sola lettura [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/it/aspose.slides.charts/chart/axes/) | Fornisce l'accesso agli assi del grafico Chart.<br/>            Sola lettura [`IAxesManager`](/slides/python-net/it/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/it/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Specifica se le etichette dei dati al di sopra del massimo del grafico devono essere mostrate.<br/>            Lettura/Scrittura **bool**. |
| [`has_rounded_corners`](/slides/python-net/it/aspose.slides.charts/chart/has_rounded_corners/) | Specifica se l'area del grafico deve avere angoli arrotondati.<br/>            Lettura/Scrittura **bool**. |
| [`chart`](/slides/python-net/it/aspose.slides.charts/chart/chart/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides.charts/chart/get_image/#) | Restituisce la miniatura della forma.<br/>            Il tipo ShapeThumbnailBounds.Shape per i limiti della miniatura della forma è usato di default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Restituisce la miniatura della forma. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Salva il contenuto della Shape come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della Shape come file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides.charts/chart/remove_placeholder/#) | Definisce che questa forma non è un segnaposto. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Aggiunge un nuovo segnaposto se non presente e imposta le proprietà del segnaposto su quello specificato. |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides.charts/chart/get_base_placeholder/#) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla slide master da cui la forma corrente è ereditata).<br/>            Viene restituito None se la forma corrente non è ereditata. |
| [`get_visual_bounds(self)`](/slides/python-net/it/aspose.slides.charts/chart/get_visual_bounds/#) | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [`validate_chart_layout(self)`](/slides/python-net/it/aspose.slides.charts/chart/validate_chart_layout/#) | Calcola i valori effettivi degli elementi del grafico. I valori effettivi includono la posizione degli elementi che implementano l'interfaccia IActualLayout <br/>(IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/> e i valori effettivi degli assi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit,<br/> IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides.charts/chart/create_theme_effective/#) | Restituisce un tema efficace per questo grafico Chart. |

### Vedi anche
* classe [`Chart`](/slides/python-net/it/aspose.slides.charts/chart)
* classe [`GraphicalObject`](/slides/python-net/it/aspose.slides/graphicalobject)
* classe [`Shape`](/slides/python-net/it/aspose.slides/shape)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)