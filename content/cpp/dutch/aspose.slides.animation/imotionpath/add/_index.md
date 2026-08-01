---
title: Add()
second_title: Aspose.Slides voor C++ API Referentie
description: Voeg nieuw commando toe aan pad
type: docs
weight: 14
url: /nl/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) methode

Add new command to path

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Type van commando voor animatiebewegings effectgedrag [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Puntenarray [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Type van punten in animatiebewegings pad [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Geeft aan of relatieve coördinaten al dan niet worden gebruikt **bool** |

### Retourwaarde

Commando van een pad [IMotionCmdPath](../../imotioncmdpath/)

## Zie ook

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IMotionCmdPath](../../imotioncmdpath/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Klasse [IMotionPath](../)
* Naamruimte [Aspose::Slides::Animation](../../)
* Bibliotheek [Aspose.Slides](../../../)