---
title: Process()
second_title: Aspose.Slides untuk Referensi API C++
description: Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.
type: docs
weight: 1
url: /id/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) metode


Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.
```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Array berisi nama file presentasi input. |
| outputFileName | [System::String](../../../system/string/) | Nama file output dari file presentasi hasil penggabungan. |
## Catatan




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) metode
Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Array yang berisi nama file presentasi masukan. |
| outputFileName | [System::String](../../../system/string/) | Nama file keluaran dari file presentasi gabungan yang dihasilkan. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opsi tambahan yang menentukan cara penyimpanan presentasi yang digabungkan. |
## Catatan

```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) metode

Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.
```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Sebuah array berisi nama-nama file presentasi input. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream output. |
## Catatan




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) method


Menggabungkan beberapa presentasi PowerPoint dengan format yang sama menjadi satu file presentasi.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Sebuah array berisi nama-nama file presentasi input. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream output. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opsi tambahan yang menentukan cara penyimpanan presentasi yang digabungkan. |
## Catatan




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [Merger](../)
* Kelas [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Kelas [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::LowCode](../../)
* Pustaka [Aspose.Slides](../../../)