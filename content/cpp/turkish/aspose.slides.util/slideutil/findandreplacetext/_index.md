---
title: FindAndReplaceText()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda verilen biçimle metni bulur ve değiştirir
type: docs
weight: 40
url: /tr/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) method

Sunumda verilen biçimle metni bulur ve değiştirir

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Taranmış sunum. |
| withMasters | **bool** | Ana slaytların taranıp taranmayacağını belirler. |
| find | [System::String](../../../system/string/) | Bulunacak dize değeri. |
| replace | [System::String](../../../system/string/) | Değiştirilecek dize değeri. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Metin bölümünü değiştirmek için biçim. Null ise bulunan dizedeki ilk karakterin biçimi kullanılacak. |

## Açıklamalar

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

## Diğer Bağlantılar

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPresentation](../../../aspose.slides/ipresentation/)
* Sınıf [String](../../../system/string/)
* Sınıf [PortionFormat](../../../aspose.slides/portionformat/)
* Sınıf [SlideUtil](../)
* Ad Alanı [Aspose::Slides::Util](../../)
* Kütüphane [Aspose.Slides](../../../)