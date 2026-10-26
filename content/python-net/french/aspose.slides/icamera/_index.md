---
title: ICamera class
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides/icamera/
---
## classe ICamera

Représente Camera.

Le type ICamera expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/fr/aspose.slides/icamera/camera_type/) | type de caméra<br/>            Lecture/écriture [`CameraPresetType`](/slides/python-net/fr/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/fr/aspose.slides/icamera/field_of_view_angle/) | FOV de la caméra (0-180 deg, champ de vision)<br/>            Lecture/écriture **float**. |
| [`zoom`](/slides/python-net/fr/aspose.slides/icamera/zoom/) | Zoom de la caméra (valeur positive en pourcentage)<br/>            Lecture/écriture **float**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/fr/aspose.slides/icamera/set_rotation/#float-float-float) | Une rotation est définie par l'utilisation d'une coordonnée de latitude<br/>            d'une coordonnée de longitude et d'une révolution autour de l'axe <br/>            comme les coordonnées de latitude et de longitude.<br/>            Si une valeur de coordonnée est float.NaN, toute rotation est indéfinie. |
| [`get_rotation(self)`](/slides/python-net/fr/aspose.slides/icamera/get_rotation/#) | Une rotation est définie par l'utilisation d'une coordonnée de latitude<br/>            d'une coordonnée de longitude et d'une révolution autour de l'axe <br/>            comme les coordonnées de latitude et de longitude.<br/>            premier élément du tableau retourné - latitude, deuxième - longitude, troisième - révolution.<br/>            Retourne None si aucune rotation n'est définie. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)