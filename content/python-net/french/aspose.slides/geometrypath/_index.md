---
title: GeometryPath class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/geometrypath/
---
## GeometryPath classe

Représente le chemin géométrique de GeometryShape

Le type GeometryPath expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides/geometrypath/__init__/#) | Crée une instance de GeometryPath |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`path_data`](/slides/python-net/fr/aspose.slides/geometrypath/path_data/) | Renvoie le chemin géométrique de GeometryShape sous forme de tableau de segments de chemin. |
| [`fill_mode`](/slides/python-net/fr/aspose.slides/geometrypath/fill_mode/) | Définit le mode de remplissage |
| [`stroke`](/slides/python-net/fr/aspose.slides/geometrypath/stroke/) | Définit l'apparence du trait |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/fr/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Ajoute une ligne à la fin du chemin |
| [`line_to(self, x, y)`](/slides/python-net/fr/aspose.slides/geometrypath/line_to/#float-float) | Ajoute une ligne à la fin du chemin |
| [`line_to(self, point, index)`](/slides/python-net/fr/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Ajoute une ligne à l'endroit spécifié du chemin |
| [`line_to(self, x, y, index)`](/slides/python-net/fr/aspose.slides/geometrypath/line_to/#float-float-int) | Ajoute une ligne à l'endroit spécifié du chemin |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/fr/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Ajoute une courbe de Bézier cubique à la fin du chemin |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/fr/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Ajoute une courbe de Bézier cubique à la fin du chemin |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/fr/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Ajoute une courbe de Bézier cubique à l'endroit spécifié du chemin |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/fr/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Ajoute une courbe de Bézier cubique à l'endroit spécifié du chemin |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/fr/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Ajoute une courbe de Bézier quadratique à la fin du chemin |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/fr/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Ajoute une courbe de Bézier quadratique à la fin du chemin |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/fr/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Ajoute une courbe de Bézier quadratique à l'endroit spécifié du chemin |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/fr/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Ajoute une courbe de Bézier quadratique à l'endroit spécifié du chemin |
| [`move_to(self, point)`](/slides/python-net/fr/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Définit la position du point suivant. |
| [`move_to(self, x, y)`](/slides/python-net/fr/aspose.slides/geometrypath/move_to/#float-float) | Définit la position du point suivant. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides/geometrypath/remove_at/#int) | Supprime le segment à l'index spécifié du chemin géométrique. |
| [`close_figure(self)`](/slides/python-net/fr/aspose.slides/geometrypath/close_figure/#) | Ferme la figure actuelle de ce chemin |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/fr/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Ajoute l'arc spécifié au chemin. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)