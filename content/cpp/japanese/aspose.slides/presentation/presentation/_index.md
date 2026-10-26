---
title: Presentation()
second_title: Aspose.Slides for C++ API リファレンス
description: このコンストラクタは新しいプレゼンテーションをゼロから作成します。作成されたプレゼンテーションには空のスライドが1枚含まれます。
type: docs
weight: 417
url: /ja/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() コンストラクタ

このコンストラクタは新しいプレゼンテーションをゼロから作成します。作成されたプレゼンテーションには空のスライドが1枚含まれます。

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) コンストラクタ

このコンストラクタは新しいプレゼンテーションをゼロから作成します。作成されたプレゼンテーションには空のスライドが1枚含まれます。

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | 追加のロードオプションです。 |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) コンストラクタ

このコンストラクタは既存の [Presentation](../) を読み込むための主要なメカニズムです。

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 入力ストリームです。 |
## 備考

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) コンストラクタ

このコンストラクタは既存の [Presentation](../) を読み込むための主要なメカニズムです。

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 入力ストリームです。 |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | 追加のロードオプションです。 |

## Presentation::Presentation(System::String) コンストラクタ

このコンストラクタは [Presentation](../) の内容を読み取るソースファイルパスを取得します。

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 入力ファイルです。 |
## 備考

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) コンストラクタ

このコンストラクタは [Presentation](../) の内容を読み取るソースファイルパスを取得します。

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 入力ファイルです。 |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | 追加のロードオプションです。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Presentation](../)
* クラス [LoadOptions](../../loadoptions/)
* クラス [Stream](../../../system.io/stream/)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)