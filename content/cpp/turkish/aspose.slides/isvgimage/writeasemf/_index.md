---
title: WriteAsEmf()
second_title: Aspose.Slides C++ API Referansı
description: SVG görüntüyü EMF dosyası olarak kaydeder.
type: docs
weight: 53
url: /tr/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) metot

SVG görüntüyü bir EMF dosyası olarak kaydeder.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Hedef akış |

## Açıklamalar

Aşağıdaki örnek, SVG görüntüyü bir metafile olarak kaydetmeyi gösterir. 
```cpp
// Yeni SVG görüntüsünü oluşturur
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// SVG görüntüsünü bir metafile olarak kaydeder
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
Bu örnek, SVG görüntüyü bir metafile olarak sunum görüntü koleksiyonuna eklemeyi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Yeni SVG görüntüsünü oluşturur
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// SVG görüntüsünü bir metafile olarak kaydeder
svgImage->WriteAsEmf(memStream);
// Metafile'i görüntü koleksiyonuna ekler
pres->get_Images()->AddImage(memStream->ToArray());
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [ISvgImage](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)