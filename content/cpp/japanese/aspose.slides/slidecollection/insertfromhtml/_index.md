---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API リファレンス
description: HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。
type: docs
weight: 209
url: /ja/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定した HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

Added slides.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定した HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | **bool** | このフラグは挿入の開始方法を決定します：新しいスライドから開始するか、指定されたインデックスのスライドから開始するか。**true** の場合、データの挿入は指定されたインデックスのスライドの空きスペースから開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

Added slides.

## SlideCollection::InsertFromHtml(int32_t, System::String) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |

### 戻り値

Added slides

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlText | [System::String](../../../system/string/) | 追加する HTML。 |
| useSlideWithIndexAsStart | **bool** | このフラグは挿入の開始方法を決定します：新しいスライドから開始するか、指定されたインデックスのスライドから開始するか。**true** の場合、データの挿入は指定されたインデックスのスライドの空きスペースから開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

Added slides

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML ファイルのソースとして使用される TextReader オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定した HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

Added slides.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML ファイルのソースとして使用される TextReader オブジェクト。 |

### 戻り値

Added slides

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定した HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

Added slides.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメータが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | [System::String](../../../system/string/) | 指定した HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | **bool** | このフラグは挿入の開始方法を決定します：新しいスライドから開始するか、指定されたインデックスのスライドから開始するか。**true** の場合、データの挿入は指定されたインデックスのスライドの空きスペースから開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

Added slides.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |

### 戻り値

Added slides

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) メソッド

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 挿入位置。 |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| useSlideWithIndexAsStart | **bool** | このフラグは挿入の開始方法を決定します：新しいスライドから開始するか、指定されたインデックスのスライドから開始するか。**true** の場合、データの挿入は指定されたインデックスのスライドの空きスペースから開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

Added slides

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)