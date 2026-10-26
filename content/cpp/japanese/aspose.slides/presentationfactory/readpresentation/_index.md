---
title: ReadPresentation()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列から既存のプレゼンテーションを読み取ります
type: docs
weight: 40
url: /ja/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) メソッド

既存のプレゼンテーションを配列から読み取ります

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 読み込む配列 |

### 戻り値

プレゼンテーションを読み取ります

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) メソッド

既存のプレゼンテーションを配列から読み取ります（追加のロードオプションあり）

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 読み込む配列 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ロードオプション |

### 戻り値

プレゼンテーションを読み取ります

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) メソッド

既存のプレゼンテーションをストリームから読み取ります

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 読み込む入力ストリーム |

### 戻り値

プレゼンテーションを読み取ります

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) メソッド

既存のプレゼンテーションをストリームから読み取ります（追加のロードオプションあり）

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 読み込む入力ストリーム |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ロードオプション |

### 戻り値

プレゼンテーションを読み取ります

## PresentationFactory::ReadPresentation(System::String) メソッド

既存のプレゼンテーションをファイルから読み取ります

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ファイル名 |

### 戻り値

プレゼンテーションを読み取ります

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) メソッド

既存のプレゼンテーションをファイルから読み取ります（追加のロードオプションあり）

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ファイル名 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ロードオプション |

### 戻り値

プレゼンテーションを読み取ります

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [IPresentation](../../ipresentation/)
* クラス [PresentationFactory](../)
* クラス [ILoadOptions](../../iloadoptions/)
* クラス [Stream](../../../system.io/stream/)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)