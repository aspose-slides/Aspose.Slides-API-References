---
title: ReadPresentation()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列から既存のプレゼンテーションを読み込みます
type: docs
weight: 27
url: /ja/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) メソッド

配列から既存のプレゼンテーションを読み込みます

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 読み取る配列 |

### 戻り値

プレゼンテーションを読み込む

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) メソッド

配列から既存のプレゼンテーションを追加のロードオプションと共に読み込みます

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 読み取る配列 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ロードオプション |

### 戻り値

プレゼンテーションを読み込む

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) メソッド

ストリームから既存のプレゼンテーションを読み込みます

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 読み取る入力ストリーム |

### 戻り値

プレゼンテーションを読み込む

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) メソッド

ストリームから既存のプレゼンテーションを追加のロードオプションと共に読み込みます

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 読み取る入力ストリーム |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ロードオプション |

### 戻り値

プレゼンテーションを読み込む

## IPresentationFactory::ReadPresentation(System::String) メソッド

ファイルから既存のプレゼンテーションを読み込みます

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ファイル名 |

### 戻り値

プレゼンテーションを読み込む

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) メソッド

ファイルから既存のプレゼンテーションを追加のロードオプションと共に読み込みます

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ファイル名 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ロードオプション |

### 戻り値

プレゼンテーションを読み込む

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IPresentation](../../ipresentation/)
* クラス [IPresentationFactory](../)
* クラス [ILoadOptions](../../iloadoptions/)
* クラス [Stream](../../../system.io/stream/)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)