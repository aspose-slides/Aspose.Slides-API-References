---
title: ToTiff()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi presentasi input menjadi sekumpulan gambar berformat TIFF. Jika nama file output diberikan sebagai \"myPath/myFilename.tiff\", hasilnya akan disimpan sebagai sekumpulan file \"myPath/myFilename_N.tiff\", dimana N adalah nomor slide.
type: docs
weight: 66
url: /id/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) metode

Mengonversi presentasi input menjadi sekumpulan gambar berformat TIFF. 

Jika nama file keluaran diberikan sebagai "myPath/myFilename.tiff", hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.tiff", dimana N adalah nomor slide.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi input. |
| outputFileName | [System::String](../../../system/string/) | Nama file keluaran. |

## Catatan

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) metode

Mengonversi presentasi input ke format TIFF dengan opsi khusus. Jika nama file keluaran diberikan sebagai "myPath/myFilename.tiff" dan *multipage*  adalah **false**, hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.tiff", dimana N adalah nomor slide. Jika tidak, jika *multipage*  adalah **true**, hasilnya akan menjadi dokumen multi-halaman "myPath/myFilename.tiff".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multiplane)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentasi input. |
| outputFileName | [System::String](../../../system/string/) | Nama file keluaran. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opsi penyimpanan TIFF. |
| multipage | **bool** | Menentukan apakah dokumen TIFF yang dihasilkan harus multi-halaman. |

## Catatan

```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Presentation](../../../aspose.slides/presentation/)
* Kelas [String](../../../system/string/)
* Kelas [Convert](../)
* Kelas [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Ruang Nama [Aspose::Slides::LowCode](../../)
* Pustaka [Aspose.Slides](../../../)