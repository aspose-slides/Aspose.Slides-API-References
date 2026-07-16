---
title: Insert()
second_title: Référence API Aspose.Slides for C++
description: Insérer une nouvelle commande dans le chemin
type: docs
weight: 27
url: /fr/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) méthode

Insérer une nouvelle commande dans le chemin

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indice pour l'insertion de la commande **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Type de commande pour le comportement de l'effet de mouvement d'animation [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Tableau de points [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Type de points dans le chemin de mouvement d'animation [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indique s'il faut utiliser des coordonnées relatives ou non **bool** |

## Voir aussi

* Énum [MotionCommandPathType](../../motioncommandpathtype/)
* Énum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IMotionPath](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Bibliothèque [Aspose.Slides](../../../)