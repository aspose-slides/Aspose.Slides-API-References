---
title: Table class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/table/
---
## Classe Table

Représente un tableau sur une diapositive.

**Inheritance:**[`Table`](/slides/python-net/fr/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fr/aspose.slides/shape)

Le type Table expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/table/is_text_holder/) | Détermine si la forme est TextHolder_PPT.<br/>            Lecture seule **bool**. |
| [`placeholder`](/slides/python-net/fr/aspose.slides/table/placeholder/) | Renvoie l'espace réservé d'une forme. Renvoie None si la forme n'a pas d'espace réservé.<br/>            Lecture seule [`IPlaceholder`](/slides/python-net/fr/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/table/custom_data/) | Renvoie les données personnalisées de la forme.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/table/raw_frame/) | Renvoie ou définit les propriétés du cadre brut de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fr/aspose.slides/table/frame/) | Renvoie ou définit les propriétés du cadre de la forme.<br/>            Lecture/écriture [`IShapeFrame`](/slides/python-net/fr/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fr/aspose.slides/table/line_format/) | Renvoie l'objet LineFormat qui contient les propriétés de formatage des lignes pour une forme.<br/>            Remarque : peut retourner None pour certains types de formes qui n'ont pas de propriétés de ligne.<br/>            Lecture seule [`ILineFormat`](/slides/python-net/fr/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/table/three_d_format/) | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme.<br/>            Remarque : peut retourner None pour certains types de formes qui n'ont pas de propriétés 3D.<br/>            Lecture seule [`IThreeDFormat`](/slides/python-net/fr/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fr/aspose.slides/table/effect_format/) | Renvoie l'objet EffectFormat qui contient les effets pixel appliqués à une forme.<br/>            Remarque : peut retourner None pour certains types de formes qui n'ont pas de propriétés d'effet.<br/>            Lecture seule [`IEffectFormat`](/slides/python-net/fr/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fr/aspose.slides/table/fill_format/) | Renvoie un objet TableFormat.FillFormat contenant le format de remplissage pour le Tableau.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/table/hyperlink_click/) | Renvoie ou définit le lien hypertexte défini pour le clic de souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/table/hyperlink_mouse_over/) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris.<br/>            Lecture/écriture [`IHyperlink`](/slides/python-net/fr/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/table/hyperlink_manager/) | Renvoie le gestionnaire de liens hypertexte.<br/>            Lecture seule [`IHyperlinkManager`](/slides/python-net/fr/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fr/aspose.slides/table/hidden/) | Détermine si la forme est masquée.<br/>            Lecture/écriture **bool**. |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/table/z_order_position/) | Renvoie la position d'une forme dans l'ordre Z.<br/>            Shapes[0] renvoie la forme à l'arrière de l'ordre Z,<br/>            et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z.<br/>            Lecture seule **int**. |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/table/connection_site_count/) | Renvoie le nombre de points de connexion sur la forme.<br/>            Lecture seule **int**. |
| [`rotation`](/slides/python-net/fr/aspose.slides/table/rotation/) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation dans le sens horaire ; une valeur négative indique une rotation dans le sens antihoraire.<br/>            Lecture/écriture **float**. |
| [`x`](/slides/python-net/fr/aspose.slides/table/x/) | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/table/y/) | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/table/width/) | Renvoie ou définit la largeur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/table/height/) | Renvoie ou définit la hauteur de la forme, mesurée en points.<br/>            Lecture/écriture **float**. |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/table/black_white_mode/) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc.<br/>            Lecture/écriture [`BlackWhiteMode`](/slides/python-net/fr/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fr/aspose.slides/table/unique_id/) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par les add-ins ou autre code.<br/>            Comme cette valeur peut être réaffectée par l'utilisateur ou programmatiquement, elle ne doit pas être considérée<br/>            comme une clé unique persistante.<br/>            Lecture seule **int**.<br/>            Voir également [`Shape.office_interop_shape_id`](/slides/python-net/fr/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/table/office_interop_shape_id/) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d'interopération de référencer de manière fiable la forme depuis n'importe où dans le document.<br/>            Lecture seule **int**.<br/>            Voir également [`Shape.unique_id`](/slides/python-net/fr/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/table/alternative_text/) | Renvoie ou définit le texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/table/alternative_text_title/) | Renvoie ou définit le titre du texte alternatif associé à une forme.<br/>            Lecture/écriture **str**. |
| [`name`](/slides/python-net/fr/aspose.slides/table/name/) | Renvoie ou définit le nom d'une forme.<br/>            Doit ne pas être None. Utilisez une chaîne vide si nécessaire.<br/>            Lecture/écriture **str**. |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/table/is_decorative/) | Renvoie ou définit l'option 'Marquer comme décoratif'<br/>            Lecture/écriture **bool**. |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/table/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/table/is_grouped/) | Détermine si la forme est groupée.<br/>            Lecture seule **bool**. |
| [`parent_group`](/slides/python-net/fr/aspose.slides/table/parent_group/) | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie None.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fr/aspose.slides/table/slide/) | Renvoie la diapositive parent d'une forme.<br/>            Lecture seule [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fr/aspose.slides/table/presentation/) | Renvoie la présentation parent d'une diapositive.<br/>            Lecture seule [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fr/aspose.slides/table/graphical_object_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IGraphicalObjectLock`](/slides/python-net/fr/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/fr/aspose.slides/table/rows/) | Renvoie la collection de lignes.<br/>            Lecture seule [`IRowCollection`](/slides/python-net/fr/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/fr/aspose.slides/table/columns/) | Renvoie la collection de colonnes.<br/>            Lecture seule [`IColumnCollection`](/slides/python-net/fr/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/fr/aspose.slides/table/table_format/) | Renvoie l'objet TableFormat qui contient les propriétés de formatage pour ce tableau.<br/>            Lecture seule [`ITableFormat`](/slides/python-net/fr/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/fr/aspose.slides/table/style_preset/) | Renvoie ou définit le style de tableau intégré.<br/>            Lecture/écriture [`TableStylePreset`](/slides/python-net/fr/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/fr/aspose.slides/table/right_to_left/) | Détermine si le tableau a un ordre de lecture de droite à gauche.<br/>            Lecture-écriture **bool**. |
| [`first_row`](/slides/python-net/fr/aspose.slides/table/first_row/) | Détermine si la première ligne d'un tableau doit être dessinée avec un format spécial.<br/>            Lecture/écriture **bool**. |
| [`first_col`](/slides/python-net/fr/aspose.slides/table/first_col/) | Détermine si la première colonne d'un tableau doit être dessinée avec un format spécial.<br/>            Lecture/écriture **bool**. |
| [`last_row`](/slides/python-net/fr/aspose.slides/table/last_row/) | Détermine si la dernière ligne d'un tableau doit être dessinée avec un format spécial.<br/>            Lecture/écriture **bool**. |
| [`last_col`](/slides/python-net/fr/aspose.slides/table/last_col/) | Détermine si la dernière colonne d'un tableau doit être dessinée avec un format spécial.<br/>            Lecture/écriture **bool**. |
| [`horizontal_banding`](/slides/python-net/fr/aspose.slides/table/horizontal_banding/) | Détermine si les lignes paires doivent être dessinées avec un format différent.<br/>            Lecture/écriture **bool**. |
| [`vertical_banding`](/slides/python-net/fr/aspose.slides/table/vertical_banding/) | Détermine si les colonnes paires doivent être dessinées avec un format différent.<br/>            Lecture/écriture **bool**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/table/get_image/#) | Renvoie la miniature de la forme.<br/>            Le type ShapeThumbnailBounds.Shape des limites de la miniature de la forme est utilisé par défaut. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Renvoie la miniature de la forme. |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/table/write_as_svg/#iorawiobase) | Enregistre le contenu de la forme au format SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Enregistre le contenu de la forme au format SVG. |
| [`set_text_format(self, source)`](/slides/python-net/fr/aspose.slides/table/set_text_format/#iportionformat) | Applique les propriétés de format de portion définies à toutes les portions des cellules du tableau. |
| [`set_text_format(self, source)`](/slides/python-net/fr/aspose.slides/table/set_text_format/#iparagraphformat) | Applique les propriétés de format de paragraphe définies à tous les paragraphes des cellules du tableau. |
| [`set_text_format(self, source)`](/slides/python-net/fr/aspose.slides/table/set_text_format/#itextframeformat) | Applique les propriétés de format de cadre de texte définies à tous les cadres de texte des cellules du tableau. |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/table/remove_placeholder/#) | Définit que cette forme n'est pas un espace réservé. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/table/add_placeholder/#iplaceholder) | Ajoute un nouvel espace réservé s'il n'en existe pas et définit les propriétés de l'espace réservé sur celui spécifié. |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/table/get_base_placeholder/#) | Renvoie une forme d'espace réservé de base (forme provenant de la mise en page et/ou de la diapositive maître dont la forme actuelle hérite).<br/>            Retourne None si la forme actuelle n'hérite d'aucune. |
| [`get_visual_bounds(self)`](/slides/python-net/fr/aspose.slides/table/get_visual_bounds/#) | Renvoie les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/fr/aspose.slides/table/merge_cells/#icell-icell-bool) | Fusionne les cellules voisines. |

### Voir aussi
* classe [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject)
* classe [`Shape`](/slides/python-net/fr/aspose.slides/shape)
* classe [`Table`](/slides/python-net/fr/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)