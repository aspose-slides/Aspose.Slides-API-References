---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API Referansı
description: Metin kısmı için yazım denetiminin etkin olup olmadığını gösteren bir değer ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimleri engellenir. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer false'tur.
type: docs
weight: 612
url: /tr/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) yöntemi

Metin kısmı için yazım denetiminin etkin olup olmadığını belirten bir değer ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimleri engellenir. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer **false**dır.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Açıklamalar

Aşağıdaki örnek, sunumu kaydetmeden önce SpellCheck bayrağının etkinleştirilmesini gösterir:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [BasePortionFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)