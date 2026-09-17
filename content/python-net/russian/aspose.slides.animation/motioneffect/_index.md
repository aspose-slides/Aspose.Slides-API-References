---
title: MotionEffect class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.animation/motioneffect/
---
## MotionEffect класс

Представляет поведение эффекта движения.

**Наследование:**[`MotionEffect`](/slides/python-net/ru/aspose.slides.animation/motioneffect) → [`Behavior`](/slides/python-net/ru/aspose.slides.animation/behavior)

Тип MotionEffect раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.animation/motioneffect/__init__/#) | Создает новый экземпляр. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`accumulate`](/slides/python-net/ru/aspose.slides.animation/motioneffect/accumulate/) | Указывает, накапливаются ли поведения анимации.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`additive`](/slides/python-net/ru/aspose.slides.animation/motioneffect/additive/) | Указывает, объединяется ли текущее поведение анимации с другими запущенными анимациями.<br/>            Чтение/запись [`BehaviorAdditiveType`](/slides/python-net/ru/aspose.slides.animation/behavioradditivetype). |
| [`properties`](/slides/python-net/ru/aspose.slides.animation/motioneffect/properties/) | Представляет свойства поведения.<br/>            Только чтение [`IBehaviorPropertyCollection`](/slides/python-net/ru/aspose.slides.animation/ibehaviorpropertycollection). |
| [`timing`](/slides/python-net/ru/aspose.slides.animation/motioneffect/timing/) | Представляет свойства времени для поведения эффекта.<br/>            Чтение/запись [`ITiming`](/slides/python-net/ru/aspose.slides.animation/itiming). |
| [`from_address`](/slides/python-net/ru/aspose.slides.animation/motioneffect/from_address/) | Указывает координату x/y, с которой начинается анимация (в процентах). <br/>            Чтение/запись **aspose.slides.PointF**. |
| [`to`](/slides/python-net/ru/aspose.slides.animation/motioneffect/to/) | Указывает целевую позицию для эффекта движения анимации (в процентах).<br/>            Чтение/запись **aspose.slides.PointF**. |
| [`by`](/slides/python-net/ru/aspose.slides.animation/motioneffect/by/) | Описывает относительное значение смещения для анимации (в процентах).<br/>            Чтение/запись **aspose.slides.PointF**. |
| [`rotation_center`](/slides/python-net/ru/aspose.slides.animation/motioneffect/rotation_center/) | Описывает центр вращения, используемый для поворота траектории движения на угол X.<br/>            Чтение/запись **aspose.slides.PointF**. |
| [`origin`](/slides/python-net/ru/aspose.slides.animation/motioneffect/origin/) | Указывает, к чему привязано начало траектории движения, например к разметке слайда,<br/>            или к родителю.<br/>            Чтение/запись [`MotionOriginType`](/slides/python-net/ru/aspose.slides.animation/motionorigintype). |
| [`path`](/slides/python-net/ru/aspose.slides.animation/motioneffect/path/) | Указывает примитив пути, за которым следуют координаты для движения анимации.<br/>            Чтение/запись [`IMotionPath`](/slides/python-net/ru/aspose.slides.animation/imotionpath). |
| [`path_edit_mode`](/slides/python-net/ru/aspose.slides.animation/motioneffect/path_edit_mode/) | Указывает, как траектория движения перемещается при перемещении фигуры.<br/>            Чтение/запись [`MotionPathEditMode`](/slides/python-net/ru/aspose.slides.animation/motionpatheditmode). |
| [`angle`](/slides/python-net/ru/aspose.slides.animation/motioneffect/angle/) | Описывает относительный угол траектории движения.<br/>            Чтение/запись **float**. |


### См. также
* класс [`Behavior`](/slides/python-net/ru/aspose.slides.animation/behavior)
* класс [`MotionEffect`](/slides/python-net/ru/aspose.slides.animation/motioneffect)
* модуль [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* библиотека [`Aspose.Slides`](/slides/python-net)