---
title: Insert()
second_title: Aspose.Slides C++ API referencia
description: Új parancs beszúrása az úthoz
type: docs
weight: 27
url: /hu/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method


Új parancs beszúrása az úthoz

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az parancs beszúrásához használt index **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | A parancs típusa az animációs mozgás hatás viselkedéséhez [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Ponttömb [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | A pontok típusa az animációs mozgási úton [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Megmutatja, hogy relatív koordinátákat használ-e vagy sem **bool** |

## Lásd még

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Osztály [IMotionPath](../)
* Névterület [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)