---
title: ToPng()
second_title: Aspose.Slides for C++ API Referansı
description: Giriş sunumunu PNG formatındaki bir dizi görüntüye dönüştürür. Çıktı dosya adı \"myPath/myFilename.png\" olarak verilirse, sonuç \"myPath/myFilename_N.png\" dosyaları şeklinde bir dizi olarak kaydedilir; burada N bir slayt numarasıdır.
type: docs
weight: 53
url: /tr/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) metodu

Giriş sunumunu PNG formatındaki bir dizi görüntüye dönüştürür. 

Eğer çıktı dosya adı \"myPath/myFilename.png\" olarak verilirse, sonuç \"myPath/myFilename_N.png\" dosyaları şeklinde bir dizi olarak kaydedilir; burada N bir slayt numarasıdır.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu. |
| outputFileName | [System::String](../../../system/string/) | Çıktı dosya adı. |
## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metodu

Giriş sunumunu PNG formatındaki bir dizi görüntüye dönüştürür. 

Eğer çıktı dosya adı \"myPath/myFilename.png\" olarak verilirse, sonuç \"myPath/myFilename_N.png\" dosyaları şeklinde bir dizi olarak kaydedilir; burada N bir slayt numarasıdır.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu |
| outputFileName | [System::String](../../../system/string/) | Çıktı dosya adı. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulan her görüntünün boyutu. |
## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metodu

Giriş sunumunu PNG formatındaki bir dizi görüntüye dönüştürür. 

Eğer çıktı dosya adı \"myPath/myFilename.png\" olarak verilirse, sonuç \"myPath/myFilename_N.png\" dosyaları şeklinde bir dizi olarak kaydedilir; burada N bir slayt numarasıdır.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu. |
| outputFileName | [System::String](../../../system/string/) | Çıktı dosya adı. |
| scale | **float** | Çıktı görüntülerine orijinal slayt boyutuna göre uygulanan ölçekleme faktörü. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderleme seçenekleri. |
## Açıklamalar

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [String](../../../system/string/)
* Sınıf [Convert](../)
* Sınıf [Size](../../../system.drawing/size/)
* Sınıf [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Ad alanı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)