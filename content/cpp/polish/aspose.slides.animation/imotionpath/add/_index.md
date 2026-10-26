---
title: Add()
second_title: Aspose.Slides dla C++ - odniesienie do API
description: Dodaj nową komendę do ścieżki
type: docs
weight: 14
url: /pl/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) metoda

Dodaj nową komendę do ścieżki

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Typ polecenia dla zachowania efektu ruchu animacji [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Tablica punktów [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Typ punktów w ścieżce ruchu animacji [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Wskazuje, czy używać współrzędnych względnych, czy nie **bool** |

### Wartość zwracana

Polecenie ścieżki [IMotionCmdPath](../../imotioncmdpath/)

## Zobacz także

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IMotionCmdPath](../../imotioncmdpath/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [IMotionPath](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)