---
title: get_RawFrame()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает свойства необработанной рамки фигуры. Читайте IShapeFrame.
type: docs
weight: 40
url: /ru/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() метод


Возвращает свойства необработанной рамки фигуры. Читайте [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Примечания


Код, пытающийся присвоить неопределённую рамку [IShape::set_Frame](../set_frame/), не имеет смысла в общем случае (особенно в случае, когда родитель [GroupShape](../../groupshape/) вложен несколько раз в другие GroupShape-ы). Например: 
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
 Такой код может приводить к неясным ситуациям. Поэтому были добавлены ограничения на использование неопределённых значений для [IShape::set_Frame](../set_frame/). Значения x, y, width, height, flipH, flipV и rotationAngle должны быть определены (не std::numeric_limits<float>::quiet_NaN() или [NullableBool::NotDefined](../../nullablebool/)). Приведённый выше пример кода теперь бросает исключение ArgumentException. Это относится к следующим случаям использования: 
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


Однако рамка для метода [IShape::set_RawFrame](../set_rawframe/) может быть неопределённой. Это имеет смысл, когда фигура связана с заполнителем. Тогда неопределённые значения рамки фигуры переопределяются из родительской фигуры-заполнителя. Если для этой фигуры нет родительской фигуры-заполнителя, то она использует значения по умолчанию при вычислении эффективной рамки на основе её [IShape::get_RawFrame](./). Значения по умолчанию – 0 и [NullableBool::False](../../nullablebool/) для x, y, width, height, flipH, flipV и rotationAngle. Например: 
```cpp
SharedPtr<IShape> shape = ...; // фигура связана с заполнителем
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // теперь фигура наследует значения x, y, height, flipH, flipV из заполнителя и переопределяет width=100 и rotationAngle=0.
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShapeFrame](../../ishapeframe/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)