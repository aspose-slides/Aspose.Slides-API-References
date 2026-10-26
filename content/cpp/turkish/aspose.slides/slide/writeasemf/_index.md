---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API Referansı
description: Slayt içeriğini EMF dosyası olarak kaydeder.
type: docs
weight: 170
url: /tr/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) yöntemi

Slayt içeriğini EMF dosyası olarak kaydeder.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Hedef akış |
## Açıklamalar

Aşağıdaki kod örneği, bir PowerPoint sunumunun ilk slaydını metafile biçimine nasıl dönüştüreceğinizi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// İlk slaytı metafile olarak kaydeder
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [Slide](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)