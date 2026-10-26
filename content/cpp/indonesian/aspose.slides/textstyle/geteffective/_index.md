---
title: GetEffective()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mendapatkan data pemformatan gaya teks yang efektif dengan pewarisan yang diterapkan.
type: docs
weight: 27
url: /id/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() metode

Mendapatkan data pemformatan gaya teks yang efektif dengan pewarisan yang diterapkan.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```

### Nilai Kembalian

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).

## Catatan

Contoh ini menunjukkan cara mendapatkan beberapa properti gaya teks yang efektif. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Kelas [TextStyle](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)