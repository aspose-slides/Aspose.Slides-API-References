---
title: set_RawFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece las propiedades del marco de forma bruto. Escriba IShapeFrame.
type: docs
weight: 53
url: /es/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) método


Establece las propiedades del marco de forma bruto. Escriba [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## Observaciones


Código que intenta asignar un marco indefinido a [IShape::set_Frame](../set_frame/) no tiene sentido en el caso general (particularmente cuando el padre [GroupShape](../../groupshape/) está anidado múltiples veces en otros GroupShape-s). Por ejemplo: 
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
 Ese código puede conducir a situaciones poco claras. Por ello se añadieron restricciones para usar valores indefinidos en [IShape::set_Frame](../set_frame/). Los valores de x, y, width, height, flipH, flipV y rotationAngle deben estar definidos (no std::numeric_limits<float>::quiet_NaN() o [NullableBool::NotDefined](../../nullablebool/)). El código de ejemplo anterior ahora lanza la excepción ArgumentException. Esto se aplica a los siguientes casos de uso: 
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


Pero un marco para el método [IShape::set_RawFrame](./) puede ser indefinido. Esto tiene sentido cuando la forma está vinculada a un marcador de posición. Entonces los valores indefinidos del marco de la forma se sobrescriben desde la forma del marcador de posición padre. Si no existe una forma de marcador de posición padre para esa forma, entonces esa forma usa valores predeterminados al evaluar el marco efectivo basado en su [IShape::get_RawFrame](../get_rawframe/). Los valores predeterminados son 0 y [NullableBool::False](../../nullablebool/) para x, y, width, height, flipH, flipV y rotationAngle. Por ejemplo: 
```cpp
SharedPtr<IShape> shape = ...; // shape está vinculada al marcador de posición
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ahora shape hereda los valores x, y, height, flipH, flipV del marcador de posición y sobrescribe width=100 y rotationAngle=0.
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShapeFrame](../../ishapeframe/)
* Clase [IShape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)