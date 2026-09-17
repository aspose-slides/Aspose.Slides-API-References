---
title: Chart class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chart/
---
## Chart Klasse

Stellt ein grafisches Chart auf einer Folie dar.

**Inheritance:**[`Chart`](/slides/python-net/de/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/de/aspose.slides/shape)

Der Chart-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/de/aspose.slides.charts/chart/is_text_holder/) | Bestimmt, ob die Form TextHolder_PPT ist.<br/>            Nur-Lesen **bool**. |
| [`placeholder`](/slides/python-net/de/aspose.slides.charts/chart/placeholder/) | Gibt den Platzhalter für eine Form zurück. Gibt None zurück, wenn die Form keinen Platzhalter hat.<br/>            Nur-Lesen [`IPlaceholder`](/slides/python-net/de/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/de/aspose.slides.charts/chart/custom_data/) | Gibt die benutzerdefinierten Daten der Form zurück.<br/>            Nur-Lesen [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/de/aspose.slides.charts/chart/raw_frame/) | Gibt die rohen Eigenschaften des Formrahmens zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/de/aspose.slides.charts/chart/frame/) | Gibt die Eigenschaften des Formrahmens zurück oder setzt sie.<br/>            Lesen/Schreiben [`IShapeFrame`](/slides/python-net/de/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/de/aspose.slides.charts/chart/line_format/) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine Linieneigenschaften besitzen.<br/>            Nur-Lesen [`ILineFormat`](/slides/python-net/de/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/de/aspose.slides.charts/chart/three_d_format/) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen.<br/>            Nur-Lesen [`IThreeDFormat`](/slides/python-net/de/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/de/aspose.slides.charts/chart/effect_format/) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine Effect-Eigenschaften besitzen.<br/>            Nur-Lesen [`IEffectFormat`](/slides/python-net/de/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/de/aspose.slides.charts/chart/fill_format/) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für eine Form enthält.<br/>            Hinweis: Kann None zurückgeben für bestimmte Formtypen, die keine Fülleigenschaften besitzen.<br/>            Nur-Lesen [`IFillFormat`](/slides/python-net/de/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides.charts/chart/hyperlink_click/) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides.charts/chart/hyperlink_mouse_over/) | Gibt den für Mouse-Over definierten Hyperlink zurück oder setzt ihn.<br/>            Lesen/Schreiben [`IHyperlink`](/slides/python-net/de/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides.charts/chart/hyperlink_manager/) | Gibt den Hyperlink-Manager zurück.<br/>            Nur-Lesen [`IHyperlinkManager`](/slides/python-net/de/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/de/aspose.slides.charts/chart/hidden/) | Bestimmt, ob die Form verborgen ist.<br/>            Lesen/Schreiben **bool**. |
| [`z_order_position`](/slides/python-net/de/aspose.slides.charts/chart/z_order_position/) | Gibt die Position einer Form in der Z-Reihenfolge zurück.<br/>            Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück,<br/>            und Shapes[Shapes.Count - 1] gibt die Form am vorderen Ende der Z-Reihenfolge zurück.<br/>            Nur-Lesen **int**. |
| [`connection_site_count`](/slides/python-net/de/aspose.slides.charts/chart/connection_site_count/) | Gibt die Anzahl der Verbindungspunkte der Form zurück.<br/>            Nur-Lesen **int**. |
| [`rotation`](/slides/python-net/de/aspose.slides.charts/chart/rotation/) | Gibt die Drehungsgradzahl der angegebenen Form um die Z-Achse zurück oder setzt sie.<br/>            Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert<br/>            bedeutet Drehung gegen den Uhrzeigersinn.<br/>            Lesen/Schreiben **float**. |
| [`x`](/slides/python-net/de/aspose.slides.charts/chart/x/) | Liest oder setzt die X-Koordinate der linken oberen Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`y`](/slides/python-net/de/aspose.slides.charts/chart/y/) | Liest oder setzt die Y-Koordinate der linken oberen Ecke der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`width`](/slides/python-net/de/aspose.slides.charts/chart/width/) | Liest oder setzt die Breite der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`height`](/slides/python-net/de/aspose.slides.charts/chart/height/) | Liest oder setzt die Höhe der Form, gemessen in Punkten.<br/>            Lesen/Schreiben **float**. |
| [`black_white_mode`](/slides/python-net/de/aspose.slides.charts/chart/black_white_mode/) | Die Eigenschaft gibt an, wie eine Form im Schwarz-weiß-Anzeigemodus gerendert wird.<br/>            Lesen/Schreiben [`BlackWhiteMode`](/slides/python-net/de/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/de/aspose.slides.charts/chart/unique_id/) | Gibt einen internen, presentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code bestimmt ist.<br/>            Da dieser Wert vom Benutzer oder programmgesteuert neu zugewiesen werden kann, darf er nicht als persistenter eindeutiger Schlüssel behandelt werden.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.office_interop_shape_id`](/slides/python-net/de/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides.charts/chart/office_interop_shape_id/) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der über die gesamte Lebensdauer der Form konstant bleibt und<br/>            PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren.<br/>            Nur-Lesen **int**.<br/>            Siehe auch [`Shape.unique_id`](/slides/python-net/de/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/de/aspose.slides.charts/chart/alternative_text/) | Gibt den alternativen Text zurück, der einer Form zugeordnet ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides.charts/chart/alternative_text_title/) | Gibt den Titel des alternativen Textes zurück, der einer Form zugeordnet ist, oder setzt ihn.<br/>            Lesen/Schreiben **str**. |
| [`name`](/slides/python-net/de/aspose.slides.charts/chart/name/) | Gibt den Namen einer Form zurück oder setzt ihn.<br/>            Darf nicht None sein. Verwenden Sie bei Bedarf einen leeren Zeichenkettenwert.<br/>            Lesen/Schreiben **str**. |
| [`is_decorative`](/slides/python-net/de/aspose.slides.charts/chart/is_decorative/) | Liest oder setzt die Option 'Als dekorativ markieren'<br/>            Lesen/Schreiben **bool**. |
| [`shape_lock`](/slides/python-net/de/aspose.slides.charts/chart/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur-Lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/de/aspose.slides.charts/chart/is_grouped/) | Bestimmt, ob die Form gruppiert ist.<br/>            Nur-Lesen **bool**. |
| [`parent_group`](/slides/python-net/de/aspose.slides.charts/chart/parent_group/) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird None zurückgegeben.<br/>            Nur-Lesen [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/de/aspose.slides.charts/chart/slide/) | Gibt die übergeordnete Folie einer Form zurück.<br/>            Nur-Lesen [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/de/aspose.slides.charts/chart/presentation/) | Gibt die übergeordnete Präsentation einer Folie zurück.<br/>            Nur-Lesen [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/de/aspose.slides.charts/chart/graphical_object_lock/) | Gibt die Sperren der Form zurück.<br/>            Nur-Lesen [`IGraphicalObjectLock`](/slides/python-net/de/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/de/aspose.slides.charts/chart/plot_visible_cells_only/) | Bestimmt, ob nur sichtbare Zellen geplottet werden. False, um sowohl sichtbare als auch versteckte Zellen zu plotten.<br/>            Lesen/Schreiben **bool**. |
| [`display_blanks_as`](/slides/python-net/de/aspose.slides.charts/chart/display_blanks_as/) | Gibt die Art und Weise zurück, wie leere Zellen in einem Chart geplottet werden, oder setzt sie.<br/>            Lesen/Schreiben [`DisplayBlanksAsType`](/slides/python-net/de/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/de/aspose.slides.charts/chart/chart_data/) | Gibt Informationen über die verknüpften oder eingebetteten Daten zurück, die mit einem Chart verbunden sind.<br/>            Nur-Lesen [`IChartData`](/slides/python-net/de/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/de/aspose.slides.charts/chart/has_title/) | Bestimmt, ob ein Chart einen sichtbaren Titel hat.<br/>            Lesen/Schreiben **bool**. |
| [`chart_title`](/slides/python-net/de/aspose.slides.charts/chart/chart_title/) | Gibt den Chart-Titel zurück oder setzt ihn.<br/>            Nur-Lesen [`IChartTitle`](/slides/python-net/de/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/de/aspose.slides.charts/chart/has_data_table/) | Bestimmt, ob ein Chart eine Datentabelle hat.<br/>            Lesen/Schreiben **bool**. |
| [`has_legend`](/slides/python-net/de/aspose.slides.charts/chart/has_legend/) | Bestimmt, ob ein Chart eine Legende hat.<br/>            Lesen/Schreiben **bool**. |
| [`legend`](/slides/python-net/de/aspose.slides.charts/chart/legend/) | Gibt die Legende eines Charts zurück oder setzt sie.<br/>            Nur-Lesen [`ILegend`](/slides/python-net/de/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/de/aspose.slides.charts/chart/chart_data_table/) | Gibt die Datentabelle eines Charts zurück.<br/>            Nur-Lesen [`IDataTable`](/slides/python-net/de/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/de/aspose.slides.charts/chart/style/) | Gibt den Chart-Stil zurück oder setzt ihn.<br/>            Lesen/Schreiben [`StyleType`](/slides/python-net/de/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/de/aspose.slides.charts/chart/type/) | Gibt den Chart-Typ zurück oder setzt ihn.<br/>            Lesen/Schreiben [`ChartType`](/slides/python-net/de/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/de/aspose.slides.charts/chart/plot_area/) | Stellt den Plot-Bereich eines Charts dar.<br/>            Nur-Lesen [`IChartPlotArea`](/slides/python-net/de/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/de/aspose.slides.charts/chart/rotation_3d/) | Gibt die 3D-Drehung eines Charts zurück.<br/>            Nur-Lesen [`IRotation3D`](/slides/python-net/de/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/de/aspose.slides.charts/chart/back_wall/) | Gibt ein Objekt zurück, das das Format der Rückwand eines 3D-Charts ändern lässt.<br/>            Nur-Lesen [`IChartWall`](/slides/python-net/de/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/de/aspose.slides.charts/chart/side_wall/) | Gibt ein Objekt zurück, das das Format der Seitenwand eines 3D-Charts ändern lässt.<br/>            Nur-Lesen [`IChartWall`](/slides/python-net/de/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/de/aspose.slides.charts/chart/floor/) | Gibt ein Objekt zurück, das das Format des Bodens eines 3D-Charts ändern lässt.<br/>            Nur-Lesen [`IChartWall`](/slides/python-net/de/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/de/aspose.slides.charts/chart/text_format/) | Gibt das Textformat des Charts zurück.<br/>            Die Eigenschaft gilt nicht für die folgenden Typen: [`ChartType.TREEMAP`](/slides/python-net/de/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/de/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/de/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/de/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/de/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/de/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Nur-Lesen [`IChartTextFormat`](/slides/python-net/de/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/de/aspose.slides.charts/chart/theme_manager/) | Gibt den Theme-Manager zurück.<br/>            Nur-Lesen [`IOverrideThemeManager`](/slides/python-net/de/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/de/aspose.slides.charts/chart/user_shapes/) | Gibt die über dem Chart gezeichneten Formen an.<br/>            Nur-Lesen [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/de/aspose.slides.charts/chart/axes/) | Stellt Zugriff auf die Achsen des Charts bereit.<br/>            Nur-Lesen [`IAxesManager`](/slides/python-net/de/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/de/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Gibt an, dass Datenbeschriftungen über dem Maximum des Charts angezeigt werden sollen.<br/>            Lesen/Schreiben **bool**. |
| [`has_rounded_corners`](/slides/python-net/de/aspose.slides.charts/chart/has_rounded_corners/) | Gibt an, dass der Chart-Bereich abgerundete Ecken haben soll.<br/>            Lesen/Schreiben **bool**. |
| [`chart`](/slides/python-net/de/aspose.slides.charts/chart/chart/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides.charts/chart/get_image/#) | Gibt das Form-Thumbnail zurück.<br/>            Der Typ ShapeThumbnailBounds.Shape für Form-Thumbnail-Grenzen wird standardmäßig verwendet. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Gibt das Form-Thumbnail zurück. |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Speichert den Inhalt der Form als SVG-Datei. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Speichert den Inhalt der Form als SVG-Datei. |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides.charts/chart/remove_placeholder/#) | Definiert, dass diese Form kein Platzhalter ist. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides.charts/chart/get_base_placeholder/#) | Gibt eine grundlegende Platzhalter-Form zurück (Form aus dem Layout und/oder der Master-Folien, von der die aktuelle Form erbt).<br/>            None wird zurückgegeben, wenn die aktuelle Form nicht vererbt wird. |
| [`get_visual_bounds(self)`](/slides/python-net/de/aspose.slides.charts/chart/get_visual_bounds/#) | Liest die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [`validate_chart_layout(self)`](/slides/python-net/de/aspose.slides.charts/chart/validate_chart_layout/#) | Berechnet die tatsächlichen Werte von Chart-Elementen. Die tatsächlichen Werte umfassen die Position von Elementen, die das IActualLayout-Interface implementieren <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            und die tatsächlichen Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/de/aspose.slides.charts/chart/create_theme_effective/#) | Gibt ein effektives Theme für diesen Chart zurück. |

### Siehe auch
* Klasse [`Chart`](/slides/python-net/de/aspose.slides.charts/chart)
* Klasse [`GraphicalObject`](/slides/python-net/de/aspose.slides/graphicalobject)
* Klasse [`Shape`](/slides/python-net/de/aspose.slides/shape)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)