---
title: Camera class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/camera/
---
## Classe Camera

Représente Camera.

**Héritage:**[`Camera`](/slides/python-net/fr/aspose.slides/camera) → [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)

Le type Camera expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/fr/aspose.slides/camera/camera_type/) | Type de Camera.<br/>            Lecture/écriture [`CameraPresetType`](/slides/python-net/fr/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/fr/aspose.slides/camera/field_of_view_angle/) | FOV de la Camera (0-180 deg, champ de vision).<br/>            Lecture/écriture **float**. |
| [`zoom`](/slides/python-net/fr/aspose.slides/camera/zoom/) | Zoom de la Camera (valeur positive en pourcentage).<br/>            Lecture/écriture **float**. |
| [`slide`](/slides/python-net/fr/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/camera/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/fr/aspose.slides/camera/set_rotation/#float-float-float) | Une rotation est définie à l'aide d'une coordonnée de latitude<br/>            , d'une coordonnée de longitude et d'une révolution autour de l'axe<br/>            en fonction des coordonnées de latitude et de longitude.<br/>            Si la valeur de l'une des coordonnées est float.NaN, toute rotation est indéfinie. |
| [`get_rotation(self)`](/slides/python-net/fr/aspose.slides/camera/get_rotation/#) | Une rotation est définie à l'aide d'une coordonnée de latitude<br/>            , d'une coordonnée de longitude et d'une révolution autour de l'axe<br/>            en fonction des coordonnées de latitude et de longitude.<br/>            premier élément du tableau retourné - latitude, deuxième - longitude, troisième - révolution.<br/>            Retourne None si aucune rotation n'est définie. |

### Voir aussi
* classe [`Camera`](/slides/python-net/fr/aspose.slides/camera)
* classe [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)