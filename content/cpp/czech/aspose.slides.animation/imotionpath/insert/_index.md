---
title: Insert()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vloží nový příkaz do cesty
type: docs
weight: 27
url: /cs/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) metoda


Vloží nový příkaz do cesty

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index pro vložení příkazu **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Typ příkazu pro chování efektu animace pohybu [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Pole bodů [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Typ bodů v animační dráze pohybu [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Určuje, zda použít relativní souřadnice nebo ne **bool** |

## Viz také

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [PointF](../../../system.drawing/pointf/)
* Třída [IMotionPath](../)
* Jmenný prostor [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)