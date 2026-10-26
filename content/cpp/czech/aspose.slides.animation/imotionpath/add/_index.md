---
title: Add()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá nový příkaz do cesty
type: docs
weight: 14
url: /cs/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) metoda


Přidejte nový příkaz do cesty

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Typ příkazu pro chování animačního pohybového efektu [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Pole bodů [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Typ bodů v animační cestě pohybu [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Určuje, zda použít relativní souřadnice nebo ne **bool** |

### Návratová hodnota

Příkaz cesty [IMotionCmdPath](../../imotioncmdpath/)

## Viz také

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IMotionCmdPath](../../imotioncmdpath/)
* Třída [PointF](../../../system.drawing/pointf/)
* Třída [IMotionPath](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)