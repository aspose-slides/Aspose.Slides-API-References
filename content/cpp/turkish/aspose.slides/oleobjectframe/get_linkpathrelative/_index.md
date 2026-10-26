---
title: get_LinkPathRelative()
second_title: Aspose.Slides for C++ API Referansı
description: "Mevcutsa bağlanmış bir dosyanın göreceli yolunu döndürür, aksi takdirde boş bir dize döndürür. Salt okunur System::String."
type: docs
weight: 131
url: /tr/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() metodu

Mevcutsa bağlanmış bir dosyanın göreceli yolunu döndürür, aksi takdirde boş bir string döndürür. Yalnızca okuma [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Açıklamalar

Ppt sunumlarında, bazı Ole nesne bağlantıları göreceli bir temsile sahip olabilir. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [OleObjectFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)