---
title: set_SpellCheck()
second_title: Aspose.Slides için C++ API Referansı
description: Metin bölümünde imla denetiminin etkin olup olmadığını gösteren bir değer ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimleri bastırılır. true olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer false'tur.
type: docs
weight: 612
url: /tr/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) metodu

Metin bölümünde imla denetiminin etkin olup olmadığını gösteren bir değer ayarlar. Bu özellik false olarak ayarlandığında, metin öğeleri için imla denetimleri bastırılır. true olarak ayarlandığında, imla denetimine izin verilir. Varsayılan değer **false**dır.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## Açıklamalar

Aşağıdaki örnek, sunumu kaydetmeden önce SpellCheck bayrağını etkinleştirmeyi gösterir:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// İlk slayttaki ilk şeklin içindeki metnin ilk kısmına erişin
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Bu metin bölümü için imla denetimini etkinleştir
portion->get_PortionFormat()->set_SpellCheck(true);
// Değiştirilmiş sunumu kaydedin
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Sınıf [IBasePortionFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)