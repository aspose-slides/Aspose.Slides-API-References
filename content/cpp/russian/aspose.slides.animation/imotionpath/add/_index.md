---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавить новую команду в путь
type: docs
weight: 14
url: /ru/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method

Добавить новую команду в путь

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | Тип команды для поведения анимационного эффекта движения [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | Массив точек [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | Тип точек в пути анимационного движения [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | Указывает, использовать ли относительные координаты или нет **bool** |

### Возвращаемое значение

Команда пути [IMotionCmdPath](../../imotioncmdpath/)

## См. также

* Перечисление [MotionCommandPathType](../../motioncommandpathtype/)
* Перечисление [MotionPathPointsType](../../motionpathpointstype/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [IMotionCmdPath](../../imotioncmdpath/)
* Класс [PointF](../../../system.drawing/pointf/)
* Класс [IMotionPath](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)