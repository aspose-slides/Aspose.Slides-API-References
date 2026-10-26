---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une nouvelle commande au chemin
type: docs
weight: 14
url: /fr/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) méthode


Ajoute une nouvelle commande au chemin

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Type de commande pour le comportement de l'effet de mouvement d'animation [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Tableau de points [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Type de points dans le chemin de mouvement d'animation [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Indique s’il faut utiliser des coordonnées relatives ou non **bool** |

### Valeur de retour

Commande du chemin [IMotionCmdPath](../../imotioncmdpath/)

## Voir aussi

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IMotionCmdPath](../../imotioncmdpath/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IMotionPath](../)
* Espace de noms [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)