---
title: get_SpellCheck()
second_title: Aspose.Slides için C++ API Referansı
description: Metin bölümünde imla denetiminin etkin olup olmadığını gösteren bir değer alır. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi bastırılır. True olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer false.
type: docs
weight: 599
url: /tr/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() metodu

Metin bölümünde imla denetiminin etkin olup olmadığını gösteren bir değer alır. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimi bastırılır. true olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
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

## Ayrıca bakınız

* Sınıf [IBasePortionFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)