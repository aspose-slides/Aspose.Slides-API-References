---
title: ToJpeg()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG. Jika nama file output diberikan sebagai \"myPath/myFilename.jpeg\", hasilnya akan disimpan sebagai sekumpulan file \"myPath/myFilename_N.jpeg\", di mana N adalah nomor slide.
type: docs
weight: 40
url: /id/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) metode


Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG. 

Jika nama file output diberikan sebagai \"myPath/myFilename.jpeg\", hasilnya akan disimpan sebagai sekumpulan file \"myPath/myFilename_N.jpeg\", di mana N adalah nomor slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi input. |
| outputFileName | [System::String](../../../system/string/) | Nama file output. |
## Catatan




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metode


Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG. 

Jika nama file output diberikan sebagai \"myPath/myFilename.jpeg\", hasilnya akan disimpan sebagai sekumpulan file \"myPath/myFilename_N.jpeg\", di mana N adalah nomor slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi input |
| outputFileName | [System::String](../../../system/string/) | Nama file output. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran masing-masing gambar yang dihasilkan. |
## Catatan




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metode


Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG. 

Jika nama file output diberikan sebagai \"myPath/myFilename.jpeg\", hasilnya akan disimpan sebagai sekumpulan file \"myPath/myFilename_N.jpeg\", di mana N adalah nomor slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi input. |
| outputFileName | [System::String](../../../system/string/) | Nama file output. |
| scale | **float** | Faktor skala yang diterapkan pada gambar output relatif terhadap ukuran slide asli. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
## Catatan




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Presentation](../../../aspose.slides/presentation/)
* Kelas [String](../../../system/string/)
* Kelas [Convert](../)
* Kelas [Size](../../../system.drawing/size/)
* Kelas [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)