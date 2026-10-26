---
title: Chart class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chart/
---
## Classe Chart

Représente un graphique sur une diapositive.

**Inheritance:**[`Chart`](/slides/python-net/fr/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type Chart expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides.charts/chart/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides.charts/chart/placeholder/) | Renvoie l'espace réservé d'une forme. Renvoie None si la forme n'a pas d'espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides.charts/chart/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides.charts/chart/raw_frame/) | Renvoie ou définit les propriétés du cadre brut de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides.charts/chart/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides.charts/chart/line_format/) | Renvoie l'objet LineFormat qui contient les propriétés de format de ligne pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides.charts/chart/three_d_format/) | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides.charts/chart/effect_format/) | Renvoie l'objet EffectFormat qui contient les effets pixélisés appliqués à une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés d'effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides.charts/chart/fill_format/) | Renvoie l'objet FillFormat qui contient les propriétés de format de remplissage pour une forme.<br/>            Remarque : peut renvoyer None pour certains types de formes qui n'ont pas de propriétés de remplissage.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides.charts/chart/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides.charts/chart/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides.charts/chart/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides.charts/chart/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides.charts/chart/z_order_position/) | Renvoie la position d'une forme dans l'ordre Z.<br/>            Shapes[0] renvoie la forme au fond de l'ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides.charts/chart/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides.charts/chart/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme autour de l'axe Z.<br/>            Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides.charts/chart/x/) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides.charts/chart/y/) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides.charts/chart/width/) | Obtient ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides.charts/chart/height/) | Obtient ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides.charts/chart/black_white_mode/) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc.<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides.charts/chart/unique_id/) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par les modules complémentaires ou autre code.<br/>            Étant donné que cette valeur peut être réassignée par l'utilisateur ou par programme, elle ne doit pas être traitée comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir également [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides.charts/chart/office_interop_shape_id/) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d'interopérabilité de référencer la forme de manière fiable depuis n'importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir également [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides.charts/chart/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides.charts/chart/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides.charts/chart/name/) | Renvoie ou définit le nom d'une forme.<br/>            Doit ne pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides.charts/chart/is_decorative/) | Obtient ou définit l'option « Marquer comme décoratif »<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides.charts/chart/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides.charts/chart/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides.charts/chart/parent_group/) | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/chart/slide/) | Renvoie la diapositive parent d'une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/chart/presentation/) | Renvoie la présentation parent d'une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fr/aspose.slides.charts/chart/graphical_object_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/fr/aspose.slides.charts/chart/plot_visible_cells_only/) | Détermine si seules les cellules visibles sont tracées. False pour tracer à la fois les cellules visibles et masquées.<br/>            Lecture/écriture **bool**. |
| [`display_blanks_as`](/slides/python-net/fr/aspose.slides.charts/chart/display_blanks_as/) | Renvoie ou définit la façon de tracer les cellules vides sur un graphique.<br/>            Lecture/écriture [`DisplayBlanksAsType`](/slides/python-net/fr/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/fr/aspose.slides.charts/chart/chart_data/) | Renvoie les informations sur les données liées ou intégrées associées à un graphique.<br/>            Lecture seule [`IChartData`](/slides/python-net/fr/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/fr/aspose.slides.charts/chart/has_title/) | Détermine si un graphique possède un titre visible.<br/>            Lecture/écriture **bool**. |
| [`chart_title`](/slides/python-net/fr/aspose.slides.charts/chart/chart_title/) | Renvoie ou définit le titre d'un graphique.<br/>            Lecture seule [`IChartTitle`](/slides/python-net/fr/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/fr/aspose.slides.charts/chart/has_data_table/) | Détermine si un graphique possède un tableau de données.<br/>            Lecture/écriture **bool**. |
| [`has_legend`](/slides/python-net/fr/aspose.slides.charts/chart/has_legend/) | Détermine si un graphique possède une légende.<br/>            Lecture/écriture **bool**. |
| [`legend`](/slides/python-net/fr/aspose.slides.charts/chart/legend/) | Renvoie ou définit une légende pour un graphique.<br/>            Lecture seule [`ILegend`](/slides/python-net/fr/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/fr/aspose.slides.charts/chart/chart_data_table/) | Renvoie le tableau de données d'un graphique.<br/>            Lecture seule [`IDataTable`](/slides/python-net/fr/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/fr/aspose.slides.charts/chart/style/) | Renvoie ou définit le style du graphique.<br/>            Lecture/écriture [`StyleType`](/slides/python-net/fr/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/fr/aspose.slides.charts/chart/type/) | Renvoie ou définit le type du graphique.<br/>            Lecture/écriture [`ChartType`](/slides/python-net/fr/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/fr/aspose.slides.charts/chart/plot_area/) | Représente la zone de traçage d'un graphique.<br/>            Lecture seule [`IChartPlotArea`](/slides/python-net/fr/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/fr/aspose.slides.charts/chart/rotation_3d/) | Renvoie une rotation 3D d'un graphique.<br/>            Lecture seule [`IRotation3D`](/slides/python-net/fr/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/fr/aspose.slides.charts/chart/back_wall/) | Renvoie un objet permettant de modifier le format du mur arrière d'un graphique 3D.<br/>            Lecture seule [`IChartWall`](/slides/python-net/fr/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/fr/aspose.slides.charts/chart/side_wall/) | Renvoie un objet permettant de modifier le format du mur latéral d'un graphique 3D.<br/>            Lecture seule [`IChartWall`](/slides/python-net/fr/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/fr/aspose.slides.charts/chart/floor/) | Renvoie un objet permettant de modifier le format du sol d'un graphique 3D.<br/>            Lecture seule [`IChartWall`](/slides/python-net/fr/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/fr/aspose.slides.charts/chart/text_format/) | Renvoie le format du texte du graphique.<br/>            La propriété ne s'applique pas aux types suivants : [`ChartType.TREEMAP`](/slides/python-net/fr/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/fr/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/fr/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/fr/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/fr/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/fr/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Lecture seule [`IChartTextFormat`](/slides/python-net/fr/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/fr/aspose.slides.charts/chart/theme_manager/) | Renvoie le gestionnaire de thème.<br/>            Lecture seule [`IOverrideThemeManager`](/slides/python-net/fr/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/fr/aspose.slides.charts/chart/user_shapes/) | Spécifie les formes dessinées au-dessus du graphique.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/fr/aspose.slides.charts/chart/axes/) | Fournit l'accès aux axes du graphique.<br/>            Lecture seule [`IAxesManager`](/slides/python-net/fr/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/fr/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Spécifie si les étiquettes de données au maximum du graphique doivent être affichées.<br/>            Lecture/écriture **bool**. |
| [`has_rounded_corners`](/slides/python-net/fr/aspose.slides.charts/chart/has_rounded_corners/) | Spécifie que la zone du graphique doit avoir des coins arrondis.<br/>            Lecture/écriture **bool**. |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/chart/chart/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides.charts/chart/get_image/#) | Renvoie la miniature de la forme.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme sous forme de fichier SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme sous forme de fichier SVG. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides.charts/chart/remove_placeholder/#) | Définit que cette forme n'est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s'il n'existe pas et définit les propriétés de l'espace réservé à une valeur spécifiée. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides.charts/chart/get_base_placeholder/#) | Renvoie une forme d'espace réservé de base (forme provenant de la disposition et/ou de la diapositive maîtresse dont la forme actuelle hérite).<br/>            Un None est renvoyé si la forme actuelle n'hérite pas. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides.charts/chart/get_visual_bounds/#) | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [`validate_chart_layout(self)`](/slides/python-net/fr/aspose.slides.charts/chart/validate_chart_layout/#) | Calcule les valeurs réelles des éléments du graphique. Les valeurs réelles incluent la position des éléments qui implémentent l'interface IActualLayout <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            et les valeurs réelles des axes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`create_theme_effective(self)`](/slides/python-net/fr/aspose.slides.charts/chart/create_theme_effective/#) | Renvoie un thème effectif pour ce graphique. |

### Voir aussi
* classe [`Chart`](/slides/python-net/fr/aspose.slides.charts/chart)
* classe [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)