---
title: MotionEffect
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente le comportement de l'effet de mouvement.
type: docs
weight: 590
url: /fr/aspose.slides.animation/motioneffect/
---

## Classe MotionEffect

Représente le comportement de l'effet de mouvement.

```csharp
public class MotionEffect : Behavior, IMotionEffect
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MotionEffect](motioneffect)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Accumulate](../../aspose.slides.animation/behavior/accumulate) { get; set; } | Représente si les comportements d'animation sont accumulés. Lecture/écriture [`NullableBool`](../../aspose.slides/nullablebool). |
| [Additive](../../aspose.slides.animation/behavior/additive) { get; set; } | Représente si le comportement d'animation actuel est combiné avec d'autres animations en cours. Lecture/écriture [`BehaviorAdditiveType`](../behavioradditivetype). |
| [Angle](../../aspose.slides.animation/motioneffect/angle) { get; set; } | Décrit l'angle relatif du chemin de mouvement. Lecture/écriture Single. |
| [By](../../aspose.slides.animation/motioneffect/by) { get; set; } | Décrit la valeur de décalage relative pour l'animation (en pourcentages). Lecture/écriture PointF. |
| [From](../../aspose.slides.animation/motioneffect/from) { get; set; } | Spécifie une coordonnée x/y pour commencer l'animation (en pourcentages). Lecture/écriture PointF. |
| [Origin](../../aspose.slides.animation/motioneffect/origin) { get; set; } | Spécifie ce qu'est l'origine du chemin de mouvement par rapport à la mise en page de la diapositive ou au parent. Lecture/écriture [`MotionOriginType`](../motionorigintype). |
| [Path](../../aspose.slides.animation/motioneffect/path) { get; set; } | Spécifie la primitive du chemin suivie par les coordonnées pour le mouvement de l'animation. Lecture/écriture [`IMotionPath`](../imotionpath). |
| [PathEditMode](../../aspose.slides.animation/motioneffect/patheditmode) { get; set; } | Spécifie comment le chemin de mouvement se déplace lorsque la forme est déplacée. Lecture/écriture [`MotionPathEditMode`](../motionpatheditmode). |
| [Properties](../../aspose.slides.animation/behavior/properties) { get; } | Représente les propriétés du comportement. En lecture seule [`IBehaviorPropertyCollection`](../ibehaviorpropertycollection). |
| [RotationCenter](../../aspose.slides.animation/motioneffect/rotationcenter) { get; set; } | Décrit le centre de rotation utilisé pour faire pivoter un chemin de mouvement d'un angle X. Lecture/écriture PointF. |
| [Timing](../../aspose.slides.animation/behavior/timing) { get; set; } | Représente les propriétés de timing pour le comportement de l'effet. Lecture/écriture [`ITiming`](../itiming). |
| [To](../../aspose.slides.animation/motioneffect/to) { get; set; } | Spécifie l'emplacement cible pour un effet de mouvement d'animation (en pourcentages). Lecture/écriture PointF. |

### Voir Aussi

* classe [Behavior](../behavior)
* interface [IMotionEffect](../imotioneffect)
* espace de noms [Aspose.Slides.Animation](../../aspose.slides.animation)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->