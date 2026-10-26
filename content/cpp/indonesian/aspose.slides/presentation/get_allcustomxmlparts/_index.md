---
title: get_AllCustomXmlParts()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan semua bagian data khusus dalam presentasi. Hanya-baca ICustomXmlPart[].
type: docs
weight: 287
url: /id/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() metode

Mengembalikan semua bagian data khusus dalam presentasi. Hanya-baca [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Catatan

Contoh berikut menunjukkan cara menghapus semua bagian xml khusus dari PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ICustomXmlPart](../../icustomxmlpart/)
* Kelas [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)