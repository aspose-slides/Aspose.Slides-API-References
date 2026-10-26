---
title: GetEffective()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan data pemformatan paragraf yang efektif dengan pewarisan yang diterapkan.
type: docs
weight: 365
url: /id/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() metode

Mendapatkan data pemformatan paragraf yang efektif dengan pewarisan yang diterapkan.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```

### Nilai Kembali

Sebuah [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).

## Catatan

Contoh ini menunjukkan cara memperoleh beberapa properti format paragraf yang efektif.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Kelas [ParagraphFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)