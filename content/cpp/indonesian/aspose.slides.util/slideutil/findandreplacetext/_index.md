---
title: FindAndReplaceText()
second_title: Referensi API Aspose.Slides untuk C++
description: Menemukan dan mengganti teks dalam presentasi dengan format yang diberikan
type: docs
weight: 40
url: /id/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) metode

Menemukan dan mengganti teks dalam presentasi dengan format yang diberikan

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Presentasi yang dipindai. |
| withMasters | **bool** | Menentukan apakah slide master harus dipindai. |
| find | [System::String](../../../system/string/) | Nilai string yang akan dicari. |
| replace | [System::String](../../../system/string/) | Nilai string untuk mengganti. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Format untuk mengganti bagian teks. Jika null maka akan digunakan format dari karakter pertama string yang ditemukan |

## Catatan




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```


## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPresentation](../../../aspose.slides/ipresentation/)
* Kelas [String](../../../system/string/)
* Kelas [PortionFormat](../../../aspose.slides/portionformat/)
* Kelas [SlideUtil](../)
* Ruang nama [Aspose::Slides::Util](../../)
* Perpustakaan [Aspose.Slides](../../../)