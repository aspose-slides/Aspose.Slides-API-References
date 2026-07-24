---
title: get_LinkPathRelative()
second_title: Aspose.Slides için C++ API Referansı
description: "Bağlantılı bir dosya mevcutsa, göreceli yolu döndürür, aksi takdirde boş bir dize döndürür. Salt okunur System::String."
type: docs
weight: 118
url: /tr/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() yöntemi

Bağlantılı bir dosya mevcutsa, ona göre göreceli yolu döndürür, aksi takdirde boş bir dize döndürür. Salt okunur [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Açıklamalar

Ppt sunumlarında, bazı Ole nesne bağlantılarının göreceli temsili olabilir. 

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [IOleObjectFrame](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)