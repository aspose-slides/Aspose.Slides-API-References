---
title: ToPng()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG. Jika nama file output diberikan sebagai \"myPath/myFilename.png\", hasil akan disimpan sebagai sekumpulan file \"myPath/myFilename_N.png\", di mana N adalah nomor slide.
type: docs
weight: 53
url: /id/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) metode


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG. 

Jika nama file output diberikan sebagai \"myPath/myFilename.png\", hasil akan disimpan sebagai sekumpulan file \"myPath/myFilename_N.png\", di mana N adalah nomor slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi masukan. |
| outputFileName | [System::String](../../../system/string/) | Nama file output. |
## Catatan




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metode


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG. 

Jika nama file output diberikan sebagai \"myPath/myFilename.png\", hasil akan disimpan sebagai sekumpulan file \"myPath/myFilename_N.png\", di mana N adalah nomor slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi masukan |
| outputFileName | [System::String](../../../system/string/) | Nama file output. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran setiap gambar yang dihasilkan. |
## Catatan




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metode


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG. 

Jika nama file output diberikan sebagai \"myPath/myFilename.png\", hasil akan disimpan sebagai sekumpulan file \"myPath/myFilename_N.png\", di mana N adalah nomor slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi masukan. |
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
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Presentation](../../../aspose.slides/presentation/)
* Kelas [String](../../../system/string/)
* Kelas [Convert](../)
* Kelas [Size](../../../system.drawing/size/)
* Kelas [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* RuangNama [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)