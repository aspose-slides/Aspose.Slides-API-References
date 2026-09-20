---
title: Chart class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chart/
---
## Chart klass

Representerar ett grafiskt Chart på en bild.

**Inheritance:**[`Chart`](/slides/python-net/sv/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/sv/aspose.slides/shape)

Chart-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides.charts/chart/is_text_holder/) | Determinerar om shape är TextHolder_PPT.<br/>            Skrivskyddad **bool**. |
| [`placeholder`](/slides/python-net/sv/aspose.slides.charts/chart/placeholder/) | Returnerar platshållaren för en shape. Returnerar None om shape inte har någon platshållare.<br/>            Skrivskyddad [`IPlaceholder`](/slides/python-net/sv/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/sv/aspose.slides.charts/chart/custom_data/) | Returnerar shape-ens anpassade data.<br/>            Skrivskyddad [`ICustomData`](/slides/python-net/sv/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/sv/aspose.slides.charts/chart/raw_frame/) | Returnerar eller anger de råa shape-ramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/sv/aspose.slides.charts/chart/frame/) | Returnerar eller anger shape-ramens egenskaper.<br/>            Läs/skriv [`IShapeFrame`](/slides/python-net/sv/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/sv/aspose.slides.charts/chart/line_format/) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en shape.<br/>            Obs: kan returnera None för vissa typer av shapes som saknar linjeegenskaper.<br/>            Skrivskyddad [`ILineFormat`](/slides/python-net/sv/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/sv/aspose.slides.charts/chart/three_d_format/) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en shape.<br/>            Obs: kan returnera None för vissa typer av shapes som saknar 3D-egenskaper.<br/>            Skrivskyddad [`IThreeDFormat`](/slides/python-net/sv/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/sv/aspose.slides.charts/chart/effect_format/) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en shape.<br/>            Obs: kan returnera None för vissa typer av shapes som saknar effektegenskaper.<br/>            Skrivskyddad [`IEffectFormat`](/slides/python-net/sv/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/sv/aspose.slides.charts/chart/fill_format/) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en shape.<br/>            Obs: kan returnera None för vissa typer av shapes som saknar fyllningsegenskaper.<br/>            Skrivskyddad [`IFillFormat`](/slides/python-net/sv/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides.charts/chart/hyperlink_click/) | Returnerar eller anger hyperlänken som definierats för musklick.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides.charts/chart/hyperlink_mouse_over/) | Returnerar eller anger hyperlänken som definierats för musöver.<br/>            Läs/skriv [`IHyperlink`](/slides/python-net/sv/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides.charts/chart/hyperlink_manager/) | Returnerar hyperlänks-hanteraren.<br/>            Skrivskyddad [`IHyperlinkManager`](/slides/python-net/sv/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/sv/aspose.slides.charts/chart/hidden/) | Avgör om shape är dold.<br/>            Läs/skriv **bool**. |
| [`z_order_position`](/slides/python-net/sv/aspose.slides.charts/chart/z_order_position/) | Returnerar shape-ens position i z-ordningen.<br/>            Shapes[0] returnerar shape längst bak i z-ordningen,<br/>            och Shapes[Shapes.Count - 1] returnerar shape längst fram i z-ordningen.<br/>            Skrivskyddad **int**. |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides.charts/chart/connection_site_count/) | Returnerar antalet anslutningspunkter på shape.<br/>            Skrivskyddad **int**. |
| [`rotation`](/slides/python-net/sv/aspose.slides.charts/chart/rotation/) | Returnerar eller anger antalet grader som den angivna shape roteras runt<br/>            z-axeln. Ett positivt värde innebär medurs rotation; ett negativt värde<br/>            innebär moturs rotation.<br/>            Läs/skriv **float**. |
| [`x`](/slides/python-net/sv/aspose.slides.charts/chart/x/) | Hämtar eller anger x-koordinaten för shape-ens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`y`](/slides/python-net/sv/aspose.slides.charts/chart/y/) | Hämtar eller anger y-koordinaten för shape-ens övre vänstra hörn, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`width`](/slides/python-net/sv/aspose.slides.charts/chart/width/) | Hämtar eller anger shape-ens bredd, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`height`](/slides/python-net/sv/aspose.slides.charts/chart/height/) | Hämtar eller anger shape-ens höjd, mätt i punkter.<br/>            Läs/skriv **float**. |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides.charts/chart/black_white_mode/) | Egenskapen anger hur en shape renderas i svart-vita displayläge..<br/>            Läs/skriv [`BlackWhiteMode`](/slides/python-net/sv/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/sv/aspose.slides.charts/chart/unique_id/) | Returnerar en intern, presentation-omfattande identifierare avsedd för användning av tillägg eller annan kod.<br/>            Eftersom detta värde kan omassigneras av användaren eller programatiskt, får det inte behandlas<br/>            som en bestående unik nyckel.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.office_interop_shape_id`](/slides/python-net/sv/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides.charts/chart/office_interop_shape_id/) | Returnerar en bild-omfattande unik identifierare som förblir konstant under shape-ens livslängd och<br/>            låter PowerPoint eller interop-kod pålitligt referera till shape från vilken plats i dokumentet som helst.<br/>            Skrivskyddad **int**.<br/>            Se även [`Shape.unique_id`](/slides/python-net/sv/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/sv/aspose.slides.charts/chart/alternative_text/) | Returnerar eller anger alternativ text som är associerad med en shape.<br/>            Läs/skriv **str**. |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides.charts/chart/alternative_text_title/) | Returnerar eller anger titeln för alternativ text som är associerad med en shape.<br/>            Läs/skriv **str**. |
| [`name`](/slides/python-net/sv/aspose.slides.charts/chart/name/) | Returnerar eller anger namnet på en shape.<br/>            Måste vara icke-None. Använd tom sträng vid behov.<br/>            Läs/skriv **str**. |
| [`is_decorative`](/slides/python-net/sv/aspose.slides.charts/chart/is_decorative/) | Hämtar eller anger alternativet 'Mark as decorative'<br/>            Läs/skriv **bool**. |
| [`shape_lock`](/slides/python-net/sv/aspose.slides.charts/chart/shape_lock/) | Returnerar shape-ens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/sv/aspose.slides.charts/chart/is_grouped/) | Avgör om shape är grupperad.<br/>            Skrivskyddad **bool**. |
| [`parent_group`](/slides/python-net/sv/aspose.slides.charts/chart/parent_group/) | Returnerar föräldra-GroupShape-objektet om shape är grupperad. Annars returneras None.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/sv/aspose.slides.charts/chart/slide/) | Returnerar parent-slide för en shape.<br/>            Skrivskyddad [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/sv/aspose.slides.charts/chart/presentation/) | Returnerar parent-presentation för en slide.<br/>            Skrivskyddad [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/sv/aspose.slides.charts/chart/graphical_object_lock/) | Returnerar shape-ens lås.<br/>            Skrivskyddad [`IGraphicalObjectLock`](/slides/python-net/sv/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/sv/aspose.slides.charts/chart/plot_visible_cells_only/) | Avgör om endast synliga celler plottas. False för att plotta både synliga och dolda celler.<br/>            Läs/skriv **bool**. |
| [`display_blanks_as`](/slides/python-net/sv/aspose.slides.charts/chart/display_blanks_as/) | Returnerar eller anger sättet att plotta tomma celler på en chart.<br/>            Läs/skriv [`DisplayBlanksAsType`](/slides/python-net/sv/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/sv/aspose.slides.charts/chart/chart_data/) | Returnerar information om de länkade eller inbäddade data som är associerade med en chart.<br/>            Skrivskyddad [`IChartData`](/slides/python-net/sv/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/sv/aspose.slides.charts/chart/has_title/) | Avgör om en chart har en synlig titel.<br/>            Läs/skriv **bool**. |
| [`chart_title`](/slides/python-net/sv/aspose.slides.charts/chart/chart_title/) | Returnerar eller anger en chart-titel.<br/>            Skrivskyddad [`IChartTitle`](/slides/python-net/sv/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/sv/aspose.slides.charts/chart/has_data_table/) | Avgör om en chart har en datatabell.<br/>            Läs/skriv **bool**. |
| [`has_legend`](/slides/python-net/sv/aspose.slides.charts/chart/has_legend/) | Avgör om en chart har en legend.<br/>            Läs/skriv **bool**. |
| [`legend`](/slides/python-net/sv/aspose.slides.charts/chart/legend/) | Returnerar eller anger en legend för en chart.<br/>            Skrivskyddad [`ILegend`](/slides/python-net/sv/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/sv/aspose.slides.charts/chart/chart_data_table/) | Returnerar en datatabell för en chart.<br/>            Skrivskyddad [`IDataTable`](/slides/python-net/sv/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/sv/aspose.slides.charts/chart/style/) | Returnerar eller anger chart-stilen.<br/>            Läs/skriv [`StyleType`](/slides/python-net/sv/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/sv/aspose.slides.charts/chart/type/) | Returnerar eller anger chart-typen.<br/>            Läs/skriv [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/sv/aspose.slides.charts/chart/plot_area/) | Representerar plot-området för en chart.<br/>            Skrivskyddad [`IChartPlotArea`](/slides/python-net/sv/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/sv/aspose.slides.charts/chart/rotation_3d/) | Returnerar en 3D-rotation av en chart.<br/>            Skrivskyddad [`IRotation3D`](/slides/python-net/sv/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/sv/aspose.slides.charts/chart/back_wall/) | Returnerar ett objekt som tillåter ändring av formatet på bakväggen för en 3D-chart.<br/>            Skrivskyddad [`IChartWall`](/slides/python-net/sv/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/sv/aspose.slides.charts/chart/side_wall/) | Returnerar ett objekt som tillåter ändring av formatet på sidoväggen för en 3D-chart.<br/>            Skrivskyddad [`IChartWall`](/slides/python-net/sv/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/sv/aspose.slides.charts/chart/floor/) | Returnerar ett objekt som tillåter ändring av formatet på golvet för en 3D-chart.<br/>            Skrivskyddad [`IChartWall`](/slides/python-net/sv/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/sv/aspose.slides.charts/chart/text_format/) | Returnerar chart-textformat.<br/>            Egenskapen är inte tillämplig för följande typer: [`ChartType.TREEMAP`](/slides/python-net/sv/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/sv/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/sv/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/sv/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/sv/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/sv/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Skrivskyddad [`IChartTextFormat`](/slides/python-net/sv/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/sv/aspose.slides.charts/chart/theme_manager/) | Returnerar theme-hanteraren.<br/>            Skrivskyddad [`IOverrideThemeManager`](/slides/python-net/sv/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/sv/aspose.slides.charts/chart/user_shapes/) | Specificera formerna som ritas ovanpå chart.<br/>            Skrivskyddad [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/sv/aspose.slides.charts/chart/axes/) | Tillhandahåller åtkomst till chart-axlar.<br/>            Skrivskyddad [`IAxesManager`](/slides/python-net/sv/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/sv/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Anger att datalabeler över chart-ens maximum ska visas.<br/>            Läs/skriv **bool**. |
| [`has_rounded_corners`](/slides/python-net/sv/aspose.slides.charts/chart/has_rounded_corners/) | Anger att chart-området ska ha rundade hörn.<br/>            Läs/skriv **bool**. |
| [`chart`](/slides/python-net/sv/aspose.slides.charts/chart/chart/) |  |

## Metoder

| Metod | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides.charts/chart/get_image/#) | Returnerar shape-thumbnail.<br/>            ShapeThumbnailBounds.Shape shape-thumbnail-gränser typ används som standard. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Returnerar shape-thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Sparar innehållet i Shape som SVG-fil. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Sparar innehållet i Shape som SVG-fil. |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides.charts/chart/remove_placeholder/#) | Definierar att denna shape inte är en placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Lägger till en ny placeholder om det saknas och sätter placeholder-egenskaper till en specificerad. |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides.charts/chart/get_base_placeholder/#) | Returnerar en grundläggande placeholder-shape (shape från layouten och/eller huvud-sliden som den aktuella shape ärvs från).<br/>            En None returneras om den aktuella shape inte ärvs. |
| [`get_visual_bounds(self)`](/slides/python-net/sv/aspose.slides.charts/chart/get_visual_bounds/#) | Hämtar de visuella gränserna för shape beräknade från dess renderade innehåll. |
| [`validate_chart_layout(self)`](/slides/python-net/sv/aspose.slides.charts/chart/validate_chart_layout/#) | Beräknar faktiska värden för chart-element. De faktiska värdena inkluderar positionen för element som implementerar IActualLayout-gränssnittet <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            och faktiska axelvärden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`create_theme_effective(self)`](/slides/python-net/sv/aspose.slides.charts/chart/create_theme_effective/#) | Returnerar ett effektivt tema för denna chart. |

### Se också
* klass [`Chart`](/slides/python-net/sv/aspose.slides.charts/chart)
* klass [`GraphicalObject`](/slides/python-net/sv/aspose.slides/graphicalobject)
* klass [`Shape`](/slides/python-net/sv/aspose.slides/shape)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)