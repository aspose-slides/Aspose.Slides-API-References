---
title: Process()
second_title: Aspose.Slides for C++ API リファレンス
description: 同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。
type: docs
weight: 1
url: /ja/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) メソッド


同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 入力プレゼンテーション ファイル名の配列。 |
| outputFileName | [System::String](../../../system/string/) | 結合されたプレゼンテーション ファイルの出力ファイル名。 |
## 備考




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) メソッド


同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 入力プレゼンテーション ファイル名の配列。 |
| outputFileName | [System::String](../../../system/string/) | 結合されたプレゼンテーション ファイルの出力ファイル名。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 結合されたプレゼンテーションの保存方法を定義する追加オプション。 |
## 備考




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) メソッド


同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 入力プレゼンテーション ファイル名の配列。 |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 出力ストリーム。 |
## 備考 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) メソッド


同じ形式の複数の PowerPoint プレゼンテーションを単一のプレゼンテーション ファイルに結合します。

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 入力プレゼンテーション ファイル名の配列。 |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 出力ストリーム。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 結合されたプレゼンテーションの保存方法を定義する追加オプション。 |
## 備考 




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Merger](../)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)