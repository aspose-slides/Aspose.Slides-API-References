---
title: WriteAsEmf()
second_title: Aspose.Slides için C++ API Referansı
description: SVG görüntüsünü EMF dosyası olarak kaydeder.
type: docs
weight: 66
url: /tr/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) yöntemi

SVG görüntüsünü EMF dosyası olarak kaydeder.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Hedef akış |
## Açıklamalar

Aşağıdaki örnek, SVG görüntüsünün bir metafile olarak kaydedilmesini gösterir.
```cpp
// Yeni SVG görüntüsünü oluşturur
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// SVG görüntüsünü metafile olarak kaydeder
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Bu örnek, SVG görüntüsünün bir metafile olarak sunum görüntü koleksiyonuna eklenmesini gösterir.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Yeni SVG görüntüsünü oluşturur
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// SVG görüntüsünü metafile olarak kaydeder
svgImage->WriteAsEmf(memStream);
// Metafile'i görüntü koleksiyonuna ekler
pres->get_Images()->AddImage(memStream->ToArray());
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [SvgImage](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)