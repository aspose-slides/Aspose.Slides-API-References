---
title: get_LinkPathRelative()
second_title: Referencia de API de Aspose.Slides para C++
description: "Devuelve la ruta relativa a un archivo enlazado si está presente; de lo contrario, devuelve una cadena vacía. Sólo lectura System::String."
type: docs
weight: 118
url: /es/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() método


Devuelve la ruta relativa a un archivo enlazado si está presente; de lo contrario, devuelve una cadena vacía. Sólo lectura [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Observaciones


En las presentaciones de PowerPoint, algunos enlaces de objetos Ole pueden tener una representación relativa.

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Véase también

* Clase [String](../../../system/string/)
* Clase [IOleObjectFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)