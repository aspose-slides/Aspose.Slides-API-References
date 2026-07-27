---
title: get_RawFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve las propiedades del marco sin procesar de la forma. Lea IShapeFrame.
type: docs
weight: 40
url: /es/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() método

Devuelve las propiedades del marco sin procesar de la forma. Lea [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Observaciones

El código que intenta asignar un marco indefinido a [IShape::set_Frame](../../ishape/set_frame/) no tiene sentido en el caso general (particularmente en el caso cuando el padre [GroupShape](../../groupshape/) está anidado múltiples veces dentro de otros GroupShape-s). Por ejemplo:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 o
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
Ese código puede conducir a situaciones poco claras. Por lo tanto, se han añadido restricciones para el uso de valores indefinidos para [IShape::set_Frame](../../ishape/set_frame/). Los valores de x, y, width, height, flipH, flipV y rotationAngle deben estar definidos (no std::numeric_limits<float>::quiet_NaN() o [NullableBool::NotDefined](../../nullablebool/)). El código de ejemplo anterior ahora lanza la excepción ArgumentException. Esto se aplica a los siguientes casos de uso:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // no puede estar indefinido

SharedPtr<IShapeCollection> shapes = ...;
// los parámetros x, y, width, height no pueden ser std::numeric_limits<float>::quiet_NaN():
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

Pero un marco para el método [IShape::set_RawFrame](../../ishape/set_rawframe/) puede ser indefinido. Esto tiene sentido cuando la forma está vinculada a un marcador de posición. Entonces los valores indefinidos del marco de la forma se sobrescriben con los del marcador de posición padre. Si no hay un marcador de posición padre para esa forma, entonces esa forma usa valores predeterminados al evaluar el marco efectivo basándose en su [IShape::get_RawFrame](../../ishape/get_rawframe/). Los valores predeterminados son 0 y [NullableBool::False](../../nullablebool/) para x, y, width, height, flipH, flipV y rotationAngle. Por ejemplo:
```cpp
SharedPtr<IShape> shape = ...; // la forma está vinculada al marcador de posición
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ahora la forma hereda los valores x, y, height, flipH, flipV del marcador de posición y sobrescribe width=100 y rotationAngle=0.
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IShapeFrame](../../ishapeframe/)
* Clase [Shape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)