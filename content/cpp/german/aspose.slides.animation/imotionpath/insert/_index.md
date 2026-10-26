---
title: Insert()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen Befehl zum Pfad hinzu
type: docs
weight: 27
url: /de/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) Methode


Fügt einen neuen Befehl zum Pfad hinzu

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index für das Einfügen des Befehls **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Typ des Befehls für das Animationsbewegungs-Effektverhalten [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Punkt-Array [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Typ der Punkte im Animationsbewegungspfad [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Gibt an, ob relative Koordinaten verwendet werden sollen oder nicht **bool** |

## Siehe auch

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [IMotionPath](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)