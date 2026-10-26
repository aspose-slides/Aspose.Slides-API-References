---
title: ShapeCollection class
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/shapecollection/
---
## ShapeCollection classe

Représente une collection de formes.

Le type ShapeCollection expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`parent_group`](/slides/python-net/fr/aspose.slides/shapecollection/parent_group/) | Obtient l'objet de forme de groupe parent pour la collection de formes.<br/>            Lecture seule [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape). |

Obtient l'élément à l'index spécifié.
            Lecture seule [`IShape`](/slides/python-net/fr/aspose.slides/ishape).

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides/shapecollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'ajoute<br/>            à la fin de la collection de formes. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/fr/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres, et l'ajoute<br/>            à la fin de la collection de formes. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres,<br/>            et l'insère dans la collection de formes à l'index spécifié. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Crée un nouveau graphique, l'initialise avec des données d'exemple de séries et des paramètres,<br/>            et l'insère dans la collection de formes à l'index spécifié. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/fr/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/fr/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Crée un nouveau cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes<br/>            à l'index spécifié. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/fr/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Crée un nouveau cadre Section Zoom et l'ajoute à la fin de la collection de formes. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/fr/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Crée un nouveau cadre Section Zoom avec une image prédéfinie et l'ajoute à la fin de la collection de formes. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Crée un nouveau cadre Section Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Crée un nouveau cadre Section Zoom avec une image prédéfinie et l'insère dans la<br/>            collection de formes à l'index spécifié. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/fr/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/fr/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Crée un nouveau cadre d'objet OLE et l'ajoute à la fin de la collection de formes. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/fr/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/fr/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Crée un nouveau cadre vidéo et l'ajoute à la fin de la collection de formes. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/fr/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Crée un nouveau cadre audio avec un fichier WAV intégré et l'ajoute à la fin de la<br/>            collection de formes. L'audio intégré est ajouté à la collection Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/fr/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Crée un nouveau cadre audio et l'ajoute à la fin de la collection de formes en utilisant un<br/>            objet audio existant de la liste Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Crée un nouveau cadre audio avec un fichier WAV intégré et l'insère dans la collection de formes<br/>            à l'index spécifié. L'audio intégré est ajouté à la collection Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Crée un nouveau cadre audio et l'insère dans la collection de formes à l'index spécifié<br/>            en utilisant un objet audio existant de la liste Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/fr/aspose.slides/shapecollection/to_array/#) | Crée et renvoie un tableau contenant toutes les formes. |
| [`to_array(self, start_index, count)`](/slides/python-net/fr/aspose.slides/shapecollection/to_array/#int-int) | Crée et renvoie un tableau contenant toutes les formes dans la plage spécifiée. |
| [`reorder(self, index, shape)`](/slides/python-net/fr/aspose.slides/shapecollection/reorder/#int-ishape) | Déplace la forme spécifiée à une nouvelle position au sein de la collection de formes. |
| [`reorder(self, index, shapes)`](/slides/python-net/fr/aspose.slides/shapecollection/reorder/#int-listishape) | Déplace les formes spécifiées au sein de la collection de formes, en les plaçant à partir de l'index donné. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Crée une nouvelle forme auto avec le format par défaut et l'ajoute à la fin de la<br/>            collection de formes. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fr/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Crée une nouvelle forme auto et l'ajoute à la fin de la collection de formes, éventuellement<br/>            en l'initialisant avec le format de modèle par défaut. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié,<br/>            en appliquant le format de modèle par défaut. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Crée une nouvelle forme auto et l'insère dans la collection de formes à l'index spécifié,<br/>            éventuellement en l'initialisant avec le style de modèle par défaut. |
| [`add_group_shape(self)`](/slides/python-net/fr/aspose.slides/shapecollection/add_group_shape/#) | Crée une nouvelle forme de groupe vide et l'ajoute à la fin de la collection de formes.<br/>            Le cadre du groupe s'ajustera automatiquement pour accueillir toutes les formes ajoutées. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Crée une nouvelle forme de groupe, convertit l'image SVG spécifiée en formes individuelles,<br/>            et ajoute le groupe résultant à la fin de la collection de formes. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Crée une nouvelle forme de connecteur avec le style de modèle par défaut et l'ajoute à la fin de la<br/>            collection de formes. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fr/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Crée une nouvelle forme de connecteur et l'ajoute à la fin de la collection de formes,<br/>            éventuellement en appliquant le style de modèle par défaut. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié,<br/>            en appliquant le style de modèle par défaut. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Crée une nouvelle forme de connecteur et l'insère dans la collection de formes à l'index spécifié,<br/>            éventuellement en appliquant le style de modèle par défaut. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/fr/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes.<br/>            La nouvelle forme conserve la largeur et la hauteur du `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/fr/aspose.slides/shapecollection/add_clone/#ishape) | Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes.<br/>            La forme clonée conserve la position et la taille de l'original. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié.<br/>            La nouvelle forme conserve la largeur et la hauteur du `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_clone/#int-ishape) | Crée une copie de la forme spécifiée et l'insère dans la collection de formes à l'index spécifié.<br/>            La forme clonée conserve la position et la taille de l'original. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/fr/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Crée un diagramme SmartArt et l'ajoute à la fin de la collection de formes. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Crée un nouveau cadre Résumé Zoom et l'ajoute à la fin de la collection de formes. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Crée un nouveau cadre Résumé Zoom et l'insère dans la collection de formes à l'index spécifié. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Crée un nouveau cadre vidéo et l'insère dans la collection de formes à l'index spécifié. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Crée un nouveau cadre audio lié à une piste CD et l'ajoute à la fin de la collection de formes. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Crée un nouveau cadre audio lié à une piste CD et l'insère dans la collection de formes<br/>            à l'index spécifié. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/fr/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Crée un nouveau cadre audio lié à un fichier audio externe et l'ajoute à la fin de<br/>            la collection de formes. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Crée un nouveau cadre audio lié à un fichier audio externe et l'insère dans la<br/>            collection de formes à l'index spécifié. |
| [`index_of(self, shape)`](/slides/python-net/fr/aspose.slides/shapecollection/index_of/#ishape) | Renvoie l'index basé sur zéro de la première occurrence de la forme spécifiée dans la collection. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/fr/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Crée une nouvelle forme auto rectangle pour héberger du contenu mathématique et l'ajoute à la fin de la<br/>            collection de formes. |
| [`insert_group_shape(self, index)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_group_shape/#int) | Crée une nouvelle forme de groupe vide et l'insère dans la collection de formes à l'index spécifié.<br/>            Le cadre du groupe s'ajustera automatiquement pour accueillir toutes les formes ajoutées. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/fr/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Crée un nouveau cadre d'image contenant l'image spécifiée et l'ajoute à la fin de la<br/>            collection de formes. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Crée un nouveau cadre d'image contenant l'image spécifiée et l'insère dans la collection de formes<br/>            à l'index spécifié. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/fr/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Crée une nouvelle table et l'ajoute à la fin de la collection de formes. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/fr/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Crée une nouvelle table et l'insère dans la collection de formes à l'index spécifié. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides/shapecollection/remove_at/#int) | Supprime la forme à l'index spécifié de la collection de formes. |
| [`remove(self, shape)`](/slides/python-net/fr/aspose.slides/shapecollection/remove/#ishape) | Supprime la première occurrence de la forme spécifiée de la collection de formes. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides/shapecollection/clear/#) | Supprime toutes les formes de la collection de formes. |


### Voir aussi
* classe [`IShape`](/slides/python-net/fr/aspose.slides/ishape)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)