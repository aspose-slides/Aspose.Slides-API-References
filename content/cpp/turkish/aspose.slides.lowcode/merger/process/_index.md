---
title: Process()
second_title: Aspose.Slides for C++ API Referansı
description: Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasında birleştirir.
type: docs
weight: 1
url: /tr/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) method


Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasında birleştirir.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Giriş sunum dosyası adlarının bir dizisi. |
| outputFileName | [System::String](../../../system/string/) | Birleştirilmiş sunum dosyasının çıktı dosya adı. |
## Açıklamalar




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) method


Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasında birleştirir.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Giriş sunum dosyası adlarının bir dizisi. |
| outputFileName | [System::String](../../../system/string/) | Birleştirilmiş sunum dosyasının çıktı dosya adı. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Birleştirilmiş sunumun nasıl kaydedileceğini belirleyen ek seçenekler. |
## Açıklamalar




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) method


Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasında birleştirir.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Giriş sunum dosyası adlarının bir dizisi. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Çıktı akışı. |
## Açıklamalar




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) method


Aynı formatta birden fazla PowerPoint sunumunu tek bir sunum dosyasında birleştirir.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Giriş sunum dosyası adlarının bir dizisi. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Çıktı akışı. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Birleştirilmiş sunumun nasıl kaydedileceğini belirleyen ek seçenekler. |
## Açıklamalar




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Merger](../)
* Sınıf [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Sınıf [Stream](../../../system.io/stream/)
* Ad alanı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)