---
title: get_LinkPathRelative()
second_title: Aspose.Slides C++ API referencia
description: "Visszaadja a kapcsolt fájl relatív útvonalát, ha létezik, egyébként egy üres karakterláncot ad vissza. Csak olvasható System::String."
type: docs
weight: 131
url: /hu/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() módszer


Visszaadja a kapcsolt fájl relatív útvonalát, ha létezik, egyébként üres karakterláncot ad vissza. Csak olvasható [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Megjegyzések


A Ppt bemutatókban néhány Ole objektumhivatkozás relatív ábrázolással rendelkezhet. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [OleObjectFrame](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)