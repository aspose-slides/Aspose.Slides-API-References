---
title: ToPdf()
second_title: Aspose.Slides for C++ API リファレンス
description: Presentation を PDF に変換します。
type: docs
weight: 14
url: /ja/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) メソッド

[Presentation](../../../aspose.slides/presentation/) を PDF に変換します。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 入力プレゼンテーションのパス |
| outPath | [System::String](../../../system/string/) | 出力パス |

## 備考

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) メソッド

[Presentation](../../../aspose.slides/presentation/) を PDF に変換します。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 入力プレゼンテーションのパス |
| outPath | [System::String](../../../system/string/) | 出力パス |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | 出力 PDF オプション |

## 備考

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PPdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) メソッド

[Presentation](../../../aspose.slides/presentation/) を PDF に変換します。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション |
| outPath | [System::String](../../../system/string/) | 出力パス |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) メソッド

[Presentation](../../../aspose.slides/presentation/) を PDF に変換します。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション |
| outPath | [System::String](../../../system/string/) | 出力パス |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | 出力 PDF オプション |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Convert](../)
* クラス [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)