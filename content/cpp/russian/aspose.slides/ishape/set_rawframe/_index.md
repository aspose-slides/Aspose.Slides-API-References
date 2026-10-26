---
title: set_RawFrame()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает свойства необработанной рамки фигуры. Запишите IShapeFrame.
type: docs
weight: 53
url: /ru/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) метод

Устанавливает свойства необработанной рамки фигуры. Запишите [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## Примечания

Код, который пытается присвоить неопределённую рамку [IShape::set_Frame](../set_frame/), не имеет смысла в общем случае (особенно в случае, когда родитель [GroupShape](../../groupshape/) вложен несколько раз в другие GroupShape-s). Например: 
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
Такой код может привести к неясным ситуациям. Поэтому были добавлены ограничения на использование неопределённых значений для [IShape::set_Frame](../set_frame/). Значения x, y, width, height, flipH, flipV и rotationAngle должны быть определены (не std::numeric_limits<float>::quiet_NaN() или [NullableBool::NotDefined](../../nullablebool/)). Приведённый выше пример кода теперь бросает исключение ArgumentException. Это относится к следующим случаям: 
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

Но рамка для метода [IShape::set_RawFrame](./) может быть неопределённой. Это имеет смысл, когда фигура связана с placeholder. Затем неопределённые значения рамки фигуры переопределяются из родительской placeholder-фигуры. Если для этой фигуры нет родительского placeholder, то фигура использует значения по умолчанию при вычислении эффективной рамки на основе её [IShape::get_RawFrame](../get_rawframe/). Значения по умолчанию — 0 и [NullableBool::False](../../nullablebool/) для x, y, width, height, flipH, flipV и rotationAngle. Например: 
```cpp
SharedPtr<IShape> shape = ...; // shape связан с placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // теперь shape наследует значения x, y, height, flipH, flipV из placeholder и переопределяет width=100 и rotationAngle=0.
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IShapeFrame](../../ishapeframe/)
* Класс [IShape](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)