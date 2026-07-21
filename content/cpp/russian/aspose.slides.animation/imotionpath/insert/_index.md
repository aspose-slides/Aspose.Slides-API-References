---
title: Insert()
second_title: Aspose.Slides для C++ справочник API
description: Вставить новую команду в путь
type: docs
weight: 27
url: /ru/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) метод

Вставить новую команду в путь

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс для вставки команды **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Тип команды для поведения анимационного эффекта движения [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Массив точек [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Тип точек в пути анимации движения [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Указывает, следует ли использовать относительные координаты **bool** |

## См. также

* Enum [MotionCommandPathType](../../motioncommandpathtype/)
* Enum [MotionPathPointsType](../../motionpathpointstype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [IMotionPath](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)