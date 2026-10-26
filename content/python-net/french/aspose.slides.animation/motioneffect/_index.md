---
title: MotionEffect class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.animation/motioneffect/
---
## MotionEffect classe

Représente le comportement de l'effet de mouvement d'un effet.

**Héritage:**[`MotionEffect`](/slides/python-net/fr/aspose.slides.animation/motioneffect) → [`Behavior`](/slides/python-net/fr/aspose.slides.animation/behavior)

Le type MotionEffect expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.animation/motioneffect/__init__/#) | Crée une nouvelle instance. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`accumulate`](/slides/python-net/fr/aspose.slides.animation/motioneffect/accumulate/) | Représente si les comportements d'animation sont accumulés.<br/>            Lecture/écriture [`NullableBool`](/slides/python-net/fr/aspose.slides/nullablebool). |
| [`additive`](/slides/python-net/fr/aspose.slides.animation/motioneffect/additive/) | Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours.<br/>            Lecture/écriture [`BehaviorAdditiveType`](/slides/python-net/fr/aspose.slides.animation/behavioradditivetype). |
| [`properties`](/slides/python-net/fr/aspose.slides.animation/motioneffect/properties/) | Représente les propriétés du comportement.<br/>            Lecture seule [`IBehaviorPropertyCollection`](/slides/python-net/fr/aspose.slides.animation/ibehaviorpropertycollection). |
| [`timing`](/slides/python-net/fr/aspose.slides.animation/motioneffect/timing/) | Représente les propriétés de synchronisation pour le comportement de l'effet.<br/>            Lecture/écriture [`ITiming`](/slides/python-net/fr/aspose.slides.animation/itiming). |
| [`from_address`](/slides/python-net/fr/aspose.slides.animation/motioneffect/from_address/) | Spécifie une coordonnée x/y à partir de laquelle démarrer l'animation (en pourcentage). <br/>            Lecture/écriture [`PointF`](/slides/python-net/fr/aspose.slides/pointf). |
| [`to`](/slides/python-net/fr/aspose.slides.animation/motioneffect/to/) | Spécifie l'emplacement cible pour un effet de mouvement d'animation (en pourcentage).<br/>            Lecture/écriture [`PointF`](/slides/python-net/fr/aspose.slides/pointf). |
| [`by`](/slides/python-net/fr/aspose.slides.animation/motioneffect/by/) | Décrit la valeur de décalage relatif pour l'animation (en pourcentage).<br/>            Lecture/écriture [`PointF`](/slides/python-net/fr/aspose.slides/pointf). |
| [`rotation_center`](/slides/python-net/fr/aspose.slides.animation/motioneffect/rotation_center/) | Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X.<br/>            Lecture/écriture [`PointF`](/slides/python-net/fr/aspose.slides/pointf). |
| [`origin`](/slides/python-net/fr/aspose.slides.animation/motioneffect/origin/) | Spécifie à quoi l'origine du chemin de mouvement est relative, comme la disposition de la diapositive,<br/>            ou le parent.<br/>            Lecture/écriture [`MotionOriginType`](/slides/python-net/fr/aspose.slides.animation/motionorigintype). |
| [`path`](/slides/python-net/fr/aspose.slides.animation/motioneffect/path/) | Spécifie le primitive du chemin suivi des coordonnées pour le mouvement d'animation.<br/>            Lecture/écriture [`IMotionPath`](/slides/python-net/fr/aspose.slides.animation/imotionpath). |
| [`path_edit_mode`](/slides/python-net/fr/aspose.slides.animation/motioneffect/path_edit_mode/) | Spécifie comment le chemin de mouvement se déplace lorsqu'une forme est déplacée.<br/>            Lecture/écriture [`MotionPathEditMode`](/slides/python-net/fr/aspose.slides.animation/motionpatheditmode). |
| [`angle`](/slides/python-net/fr/aspose.slides.animation/motioneffect/angle/) | Décrit l'angle relatif du chemin de mouvement.<br/>            Lecture/écriture **float**. |

### Voir aussi
* classe [`Behavior`](/slides/python-net/fr/aspose.slides.animation/behavior)
* classe [`MotionEffect`](/slides/python-net/fr/aspose.slides.animation/motioneffect)
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)