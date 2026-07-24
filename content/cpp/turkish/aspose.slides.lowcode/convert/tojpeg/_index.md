---
title: ToJpeg()
second_title: Aspose.Slides for C++ API Referansı
description: Giriş sunumunu JPEG formatındaki bir dizi görüntüye dönüştürür.  Çıktı dosya adı \"myPath/myFilename.jpeg\" olarak verilirse, sonuç \"myPath/myFilename_N.jpeg\" dosyaları şeklinde kaydedilir; burada N bir slayt numarasıdır.
type: docs
weight: 40
url: /tr/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) metodu

Giriş sunumunu JPEG formatındaki bir dizi görüntüye dönüştürür.  

If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu. |
| outputFileName | [System::String](../../../system/string/) | Çıktı dosya adı. |

## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metodu


Giriş sunumunu JPEG formatındaki bir dizi görüntüye dönüştürür.  

If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu |
| outputFileName | [System::String](../../../system/string/) | Çıktı dosya adı. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulan her görüntünün boyutu. |

## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metodu


Giriş sunumunu JPEG formatındaki bir dizi görüntüye dönüştürür.  

If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu. |
| outputFileName | [System::String](../../../system/string/) | Çıktı dosya adı. |
| scale | **float** | Orijinal slayt boyutuna göre çıktı görüntülerine uygulanan ölçekleme faktörü. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderlama seçenekleri. |

## Açıklamalar




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)