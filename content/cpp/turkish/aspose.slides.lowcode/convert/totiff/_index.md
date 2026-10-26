---
title: ToTiff()
second_title: Aspose.Slides için C++ API Referansı
description: Giriş sunumunu bir dizi TIFF biçimindeki görüntüye dönüştürür.  Çıktı dosya adı \"myPath/myFilename.tiff\" olarak verilirse, sonuç \"myPath/myFilename_N.tiff\" dosyalarının bir kümesi olarak kaydedilir; burada N bir slayt numarasıdır.
type: docs
weight: 66
url: /tr/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) method

Giriş sunumunu bir dizi TIFF formatında görüntüye dönüştürür.  

Eğer çıktı dosya adı \"myPath/myFilename.tiff\" olarak verilirse, sonuç \"myPath/myFilename_N.tiff\" dosyalarının bir kümesi olarak kaydedilir; burada N bir slayt numarasıdır.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu. |
| outputFileName | [System::String](../../../system/string/) | Çıktı dosya adı. |
## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) method

Giriş sunumunu özel seçeneklerle TIFF formatına dönüştürür. Çıktı dosya adı \"myPath/myFilename.tiff\" olarak verilirse ve *multipage* **false** ise, sonuç \"myPath/myFilename_N.tiff\" dosyalarının bir kümesi olarak kaydedilir; burada N bir slayt numarasıdır. Aksi takdirde, *multipage* **true** ise, sonuç çok sayfalı bir \"myPath/myFilename.tiff\" belgesi olur.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu. |
| outputFileName | [System::String](../../../system/string/) | Çıktı dosya adı. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | TIFF kaydetme seçenekleri. |
| multipage | **bool** | Oluşturulan TIFF belgesinin çok sayfalı olup olmayacağını belirtir. |
## Açıklamalar

```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [String](../../../system/string/)
* Sınıf [Convert](../)
* Sınıf [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Ad alanı [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)