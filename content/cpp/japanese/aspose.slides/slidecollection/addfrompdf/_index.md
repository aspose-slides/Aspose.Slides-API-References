---
title: AddFromPdf()
second_title: Aspose.Slides for C++ API リファレンス
description: PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。
type: docs
weight: 183
url: /ja/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) メソッド

PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF ドキュメントへのパス |

### 戻り値

追加されたスライド

## 備考



例:
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) メソッド

PDF ドキュメントからスライドを作成し、PDF インポートオプションを考慮してコレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF ドキュメントへのパス |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF インポートのオプション |

### 戻り値

追加されたスライド

## 備考



例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) メソッド

PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | PDF ドキュメントのソースとして使用されるストリーム |

### 戻り値

追加されたスライド

## 備考



例:
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) メソッド

PDF ドキュメントからスライドを作成し、コレクションの末尾に追加します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | PDF ドキュメントのソースとして使用されるストリーム |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF インポートのオプション |

### 戻り値

追加されたスライド

## 備考



例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// テーブル検出を設定
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISlide](../../islide/)
* クラス [String](../../../system/string/)
* クラス [SlideCollection](../)
* クラス [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)