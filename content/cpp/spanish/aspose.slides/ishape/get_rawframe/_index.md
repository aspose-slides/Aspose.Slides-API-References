---
title: get_RawFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve las propiedades del marco sin procesar de la forma. Lea IShapeFrame.
type: docs
weight: 40
url: /es/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() método

Devuelve las propiedades del marco sin procesar de la forma. Lea [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Observaciones

El código que intenta asignar un marco no definido a [IShape::set_Frame](../set_frame/) no tiene sentido en caso general (particularmente cuando el padre [GroupShape](../../groupshape/) está anidado múltiples veces dentro de otros GroupShape-s). Por ejemplo:
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
Tal código puede generar situaciones poco claras. Por lo tanto, se añadieron restricciones para el uso de valores no definidos para [IShape::set_Frame](../set_frame/). Los valores de x, y, width, height, flipH, flipV y rotationAngle deben estar definidos (no std::numeric_limits<float>::quiet_NaN() o [NullableBool::NotDefined](../../nullablebool/)). El código de ejemplo anterior ahora lanza una excepción ArgumentException. Esto se aplica a los siguientes casos de uso:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // no puede ser indefinido

SharedPtr<IShapeCollection> shapes = ...;
// Los parámetros x, y, width, height no pueden ser std::numeric_limits<float>::quiet_NaN():
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

Sin embargo, un marco para el método [IShape::set_RawFrame](../set_rawframe/) puede estar indefinido. Esto tiene sentido cuando la forma está vinculada a un marcador de posición. Entonces los valores indefinidos del marco de la forma se sobrescriben a partir de la forma de marcador de posición padre. Si no existe una forma de marcador de posición padre para esa forma, entonces esa forma utiliza valores predeterminados al evaluar el marco efectivo basado en su [IShape::get_RawFrame](./). Los valores predeterminados son 0 y [NullableBool::False](../../nullablebool/) para x, y, width, height, flipH, flipV y rotationAngle. Por ejemplo:
```cpp
SharedPtr<IShape> shape = ...; // shape está enlazado a un marcador de posición
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ahora shape hereda los valores de x, y, height, flipH, flipV del marcador de posición y sobrescribe width=100 y rotationAngle=0.
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShapeFrame](../../ishapeframe/)
* Clase [IShape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)