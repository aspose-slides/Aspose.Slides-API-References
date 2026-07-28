---
title: get_LinkPathRelative()
second_title: Aspose.Slides C++ API Referencia
description: "Visszaadja a csatolt fájl relatív útvonalát, ha létezik, egyébként egy üres karakterláncot ad vissza. Csak olvasható System::String."
type: docs
weight: 118
url: /hu/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() metódus


Visszaadja a csatolt fájl relatív útvonalát, ha létezik, egyébként egy üres karakterláncot ad vissza. Csak olvasható [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Megjegyzések


A Ppt előadásokban néhány Ole objektumhivatkozás relatív ábrázolást tartalmazhat. 


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
* Osztály [IOleObjectFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)