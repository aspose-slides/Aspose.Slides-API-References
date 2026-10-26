---
title: get_HeaderFooterManager()
second_title: Aspose.Slides for C++ API Referansı
description: Gerçek HeaderFooter yöneticisini döndürür. Salt okunur IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /tr/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() yöntemi

Gerçek HeaderFooter yöneticisini döndürür. Salt okunur [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Açıklamalar

Aşağıdaki örnek, PowerPoint [Presentation](../) [Slide](../../slide/) içinde altbilgi görünürlüğünün nasıl ayarlanacağını gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// IsFooterVisible özelliği, bir slayt altbilgi yer tutucusunun mevcut olmadığını göstermek için kullanılır.
if (!headerFooterManager->get_IsFooterVisible())
{
    // SetFooterVisibility metodu, bir slayt altbilgi yer tutucusunu görünür yapmak için kullanılır.
    headerFooterManager->SetFooterVisibility(true);
}

// IsSlideNumberVisible özelliği, bir slayt sayfa numarası yer tutucusunun mevcut olmadığını göstermek için kullanılır.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // SetSlideNumberVisibility metodu, bir slayt sayfa numarası yer tutucusunu görünür yapmak için kullanılır.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// IsDateTimeVisible özelliği, bir slayt tarih-zaman yer tutucusunun mevcut olmadığını göstermek için kullanılır.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // SetFooterVisibility metodu, bir slayt tarih-zaman yer tutucusunu görünür yapmak için kullanılır.
    headerFooterManager->SetDateTimeVisibility(true);
}

// SetFooterText metodu, slayt altbilgi yer tutucusuna metin ayarlamak için kullanılır.
headerFooterManager->SetFooterText(u"Footer text");
// SetDateTimeText metodu, slayt tarih-zaman yer tutucusuna metin ayarlamak için kullanılır.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 Aşağıdaki örnek, [Slide](../../slide/) içinde çocuk altbilgi görünürlüğünün nasıl ayarlanacağını gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Method SetFooterAndChildFootersVisibility, bir ana slayt ve tüm alt slayt altbilgi yer tutucularını görünür yapmak için kullanılır.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Method SetSlideNumberAndChildSlideNumbersVisibility, bir ana slayt ve tüm alt slayt sayfa numarası yer tutucularını görünür yapmak için kullanılır.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Method SetDateTimeAndChildDateTimesVisibility, bir ana slayt ve tüm alt slayt tarih-zaman yer tutucularını görünür yapmak için kullanılır.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Method SetFooterAndChildFootersText, bir ana slayt ve tüm alt slayt altbilgi yer tutucularına metin ayarlamak için kullanılır.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Method SetDateTimeAndChildDateTimesText, bir ana slayt ve tüm alt slayt tarih-zaman yer tutucularına metin ayarlamak için kullanılır.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Ayrıca bakınız

* Tür tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Sınıf [Presentation](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)