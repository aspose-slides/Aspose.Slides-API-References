---
title: get_LinkPathRelative()
second_title: Referencia de API de Aspose.Slides para C++
description: "Devuelve la ruta relativa a un archivo enlazado si está presente; de lo contrario, devuelve una cadena vacía. Solo lectura System::String."
type: docs
weight: 131
url: /es/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() método


Devuelve la ruta relativa a un archivo enlazado si está presente; de lo contrario, devuelve una cadena vacía. Solo lectura [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Comentarios


En las presentaciones Ppt, algunos enlaces de objetos Ole pueden tener una representación relativa. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [OleObjectFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)