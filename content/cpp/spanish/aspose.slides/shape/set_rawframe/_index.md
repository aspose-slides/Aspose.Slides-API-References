---
title: set_RawFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece las propiedades del marco crudo de la forma. Escriba IShapeFrame.
type: docs
weight: 53
url: /es/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) método

Establece las propiedades del marco crudo de la forma. Escriba [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Observaciones

El código que intenta asignar un marco indefinido a [IShape::set_Frame](../../ishape/set_frame/) no tiene sentido en el caso general (particularmente cuando el padre [GroupShape](../../groupshape/) está anidado múltiples veces dentro de otros GroupShape-s). Por ejemplo: 
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
 Ese código puede conducir a situaciones confusas. Por lo tanto, se añadieron restricciones para usar valores indefinidos para [IShape::set_Frame](../../ishape/set_frame/). Los valores de x, y, width, height, flipH, flipV y rotationAngle deben estar definidos (no std::numeric_limits<float>::quiet_NaN() o [NullableBool::NotDefined](../../nullablebool/)). El código de ejemplo anterior ahora lanza una excepción ArgumentException. Esto se aplica a los siguientes casos de uso: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // no puede ser indefinido

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

Sin embargo, un marco para el método [IShape::set_RawFrame](../../ishape/set_rawframe/) puede ser indefinido. Esto tiene sentido cuando la forma está vinculada a un marcador de posición. Entonces los valores indefinidos del marco de la forma se sobrescriben desde la forma de marcador de posición padre. Si no existe una forma de marcador de posición padre para esa forma, entonces esa forma utiliza valores predeterminados al evaluar el marco efectivo basado en su [IShape::get_RawFrame](../../ishape/get_rawframe/). Los valores predeterminados son 0 y [NullableBool::False](../../nullablebool/) para x, y, width, height, flipH, flipV y rotationAngle. Por ejemplo: 
```cpp
SharedPtr<IShape> shape = ...; // la forma está vinculada al marcador de posición
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ahora la forma hereda los valores x, y, height, flipH, flipV del marcador de posición y sobrescribe width=100 y rotationAngle=0.
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShapeFrame](../../ishapeframe/)
* Clase [Shape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)