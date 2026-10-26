---
title: WriteAsSvg()
second_title: Aspose.Slides for C++ API Referansı
description: Slayt içeriğini SVG dosyası olarak kaydeder.
type: docs
weight: 157
url: /tr/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) metod

Slayt içeriğini SVG dosyası olarak kaydeder.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Hedef akış |
## Açıklamalar

Aşağıdaki kod örneği, bir PowerPoint sunumunun ilk slaydını SVG dosyasına nasıl dönüştüreceğinizi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// İlk slaytı SVG dosyası olarak kaydeder
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) metod

Slayt içeriğini SVG dosyası olarak kaydeder.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Hedef akış |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG oluşturma seçenekleri |
## Açıklamalar

Aşağıdaki kod örneği, bir PowerPoint sunumunun ilk slaydını seçeneklerle SVG dosyasına nasıl dönüştüreceğinizi gösterir. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// İlk slaytı SVG dosyası olarak kaydeder
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## İlgili Bölümler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [Slide](../)
* Sınıf [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)