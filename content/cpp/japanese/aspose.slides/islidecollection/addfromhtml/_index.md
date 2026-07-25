---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API リファレンス
description: HTML テキストからスライドを作成し、コレクションの末尾に追加します。
type: docs
weight: 144
url: /ja/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) メソッド

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

Added slides.

## ISlideCollection::AddFromHtml(System::String) メソッド

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |

### 戻り値

Added slides

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) メソッド

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML ファイルのソースとして使用される TextReader オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

Added slides.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) メソッド

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML ファイルのソースとして使用される TextReader オブジェクト。 |

### 戻り値

Added slides

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) メソッド

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

Added slides.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) メソッド

HTML テキストからスライドを作成し、コレクションの末尾に追加します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |

### 戻り値

Added slides

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISlide](../../islide/)
* クラス [String](../../../system/string/)
* クラス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* クラス [ISlideCollection](../)
* クラス [TextReader](../../../system.io/textreader/)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)