---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen Befehl zum Pfad hinzu
type: docs
weight: 14
url: /de/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method

Fügt einen neuen Befehl zum Pfad hinzu

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Typ des Befehls für das Verhalten des Animationsbewegungseffekts [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Punkte-Array [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Typ der Punkte im Animationsbewegungspfad [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Gibt an, ob relative Koordinaten verwendet werden oder nicht **bool** |

### Rückgabewert

Befehl eines Pfads [IMotionCmdPath](../../imotioncmdpath/)

## Siehe auch

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IMotionCmdPath](../../imotioncmdpath/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [IMotionPath](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)