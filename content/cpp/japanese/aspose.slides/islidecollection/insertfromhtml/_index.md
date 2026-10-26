---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API リファレンス
description: HTML テキストからスライドを作成し、指定された位置にコレクションに挿入します。
type: docs
weight: 157
url: /ja/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

追加されたスライド。

## ISlideCollection::InsertFromHtml(int32_t, System::String) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |

### 戻り値

追加されたスライド

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML ファイルのソースとして使用される TextReader オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

追加されたスライド。

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML ファイルのソースとして使用される TextReader オブジェクト。 |

### 戻り値

追加されたスライド

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

追加されたスライド。

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |

### 戻り値

追加されたスライド

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |
| useSlideWithIndexAsStart | **bool** | このフラグは、挿入を新しいスライドから開始するか、指定されたインデックスのスライドから開始するかを決定します。**true** の場合、指定されたインデックスのスライド上の空白領域からデータ挿入が開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

追加されたスライド

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | **bool** | このフラグは、挿入を新しいスライドから開始するか、指定されたインデックスのスライドから開始するかを決定します。**true** の場合、指定されたインデックスのスライド上の空白領域からデータ挿入が開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

追加されたスライド。

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| useSlideWithIndexAsStart | **bool** | このフラグは、挿入を新しいスライドから開始するか、指定されたインデックスのスライドから開始するかを決定します。**true** の場合、指定されたインデックスのスライド上の空白領域からデータ挿入が開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

追加されたスライド

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

HTML テキストからスライドを作成し、指定した位置にコレクションに挿入します。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 挿入する位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバック オブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | **bool** | このフラグは、挿入を新しいスライドから開始するか、指定されたインデックスのスライドから開始するかを決定します。**true** の場合、指定されたインデックスのスライド上の空白領域からデータ挿入が開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

追加されたスライド。

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISlide](../../islide/)
* クラス [String](../../../system/string/)
* クラス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* クラス [ISlideCollection](../)
* クラス [TextReader](../../../system.io/textreader/)
* クラス [Stream](../../../system.io/stream/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)