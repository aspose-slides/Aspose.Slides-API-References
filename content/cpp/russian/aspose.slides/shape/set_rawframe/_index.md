---
title: set_RawFrame()
second_title: Aspose.Slides для C++ API
description: Устанавливает свойства необработанной рамки фигуры. Запишите IShapeFrame.
type: docs
weight: 53
url: /ru/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) метод

Устанавливает свойства необработанной рамки фигуры. Запишите [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Примечания

Код, который пытается присвоить неопределённую рамку [IShape::set_Frame](../../ishape/set_frame/), не имеет смысла в общем случае (особенно в случае, когда родитель [GroupShape](../../groupshape/) вложен несколько раз в другие GroupShape-s). Например: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 или 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Такой код может приводить к неясным ситуациям. Поэтому были добавлены ограничения на использование неопределённых значений для [IShape::set_Frame](../../ishape/set_frame/). Значения x, y, width, height, flipH, flipV и rotationAngle должны быть определены (не std::numeric_limits<float>::quiet_NaN() или [NullableBool::NotDefined](../../nullablebool/)). Приведённый выше пример кода теперь бросает исключение ArgumentException. Это относится к следующим сценариям: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // не может быть неопределённым

SharedPtr<IShapeCollection> shapes = ...;
// параметры x, y, width, height не могут быть std::numeric_limits<float>::quiet_NaN():
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```

Однако рамка для метода [IShape::set_RawFrame](../../ishape/set_rawframe/) может быть не определена. Это имеет смысл, когда фигура привязана к заполнителю. Затем неопределённые значения рамки фигуры переопределяются из родительской фигуры-заполнителя. Если для этой фигуры нет родительской фигуры-заполнителя, то фигура использует значения по умолчанию при вычислении эффективной рамки на основе её [IShape::get_RawFrame](../../ishape/get_rawframe/). Значения по умолчанию — 0 и [NullableBool::False](../../nullablebool/) для x, y, width, height, flipH, flipV и rotationAngle. Например: 
```cpp
SharedPtr<IShape> shape = ...; // shape привязан к placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // теперь shape наследует значения x, y, height, flipH, flipV из placeholder и переопределяет width=100 и rotationAngle=0.
```

## Смотрите также

* Типedef [SharedPtr](../../../system/sharedptr/)
* Класс [IShapeFrame](../../ishapeframe/)
* Класс [Shape](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)