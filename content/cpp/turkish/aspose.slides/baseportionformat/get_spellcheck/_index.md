---
title: get_SpellCheck()
second_title: Aspose.Slides için C++ API Referansı
description: Metin kısmı için yazım denetiminin etkin olup olmadığını gösteren bir değer alır. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimleri engellenir. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer false'tur.
type: docs
weight: 599
url: /tr/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() metot


Metin parçası için yazım denetiminin etkin olup olmadığını gösteren bir değer alır. Bu özellik false olarak ayarlandığında, metin öğeleri için yazım denetimleri engellenir. True olarak ayarlandığında, yazım denetimine izin verilir. Varsayılan değer **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Açıklamalar


Sonraki örnek, sunumu kaydetmeden önce SpellCheck bayrağını etkinleştirmeyi gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// İlk slayttaki ilk şeklin içindeki ilk metin parçasına eriş
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Bu metin parçası için yazım denetimini etkinleştir
portion->get_PortionFormat()->set_SpellCheck(true);
// Değiştirilmiş sunumu kaydet
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Sınıf [BasePortionFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)