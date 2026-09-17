---
title: SmartArtNode class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.smartart/smartartnode/
---
## SmartArtNode classe

Représente un nœud d'un objet SmartArt

Le type SmartArtNode expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`child_nodes`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/child_nodes/) | Renvoie les collections de tous les nœuds enfants du nœud actuel.<br/>            Lecture seule [`ISmartArtNodeCollection`](/slides/python-net/fr/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/shapes/) | Renvoie les collections de toutes les formes associées au nœud.<br/>            Lecture seule [`ISmartArtShapeCollection`](/slides/python-net/fr/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/text_frame/) | Renvoie le cadre de texte du nœud.<br/>            Lecture seule [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/is_assistant/) | Renvoie ou définit le nœud comme assistant.<br/>            Lecture/écriture **bool**. |
| [`level`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/level/) | Renvoie le niveau d'imbrication du nœud.<br/>            Lecture seule **int**. |
| [`bullet_fill_format`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/bullet_fill_format/) | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour le puce d'un nœud.<br/>            Remarque : peut renvoyer None pour certains types de mise en page SmartArt qui ne fournissent pas de puces pour les nœuds.<br/>            Lecture seule [`IFillFormat`](/slides/python-net/fr/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/position/) | Renvoie ou définit la position zéro-basée du nœud parmi les nœuds frères.<br/>            Lecture/écriture **int**. |
| [`is_hidden`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/is_hidden/) | Renvoie vrai si ce nœud est un nœud masqué dans le modèle de données.<br/>            Lecture seule **bool**. |
| [`organization_chart_layout`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/organization_chart_layout/) | Renvoie ou définit le type de mise en page de l'organigramme associé au nœud actuel.<br/>            Lecture/écriture [`OrganizationChartLayoutType`](/slides/python-net/fr/aspose.slides.smartart/organizationchartlayouttype). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides.smartart/smartartnode/remove/#) | Supprime le nœud actuel. |

### Voir aussi
* module [`aspose.slides.smartart`](/slides/python-net/fr/aspose.slides.smartart)
* bibliothèque [`Aspose.Slides`](/slides/python-net)