---
title: InsertFromHtml
second_title: Aspose.Sildes for .NET API リファレンス
description: HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。
type: docs
weight: 90
url: /ja/aspose.slides/islidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlText | String | 追加する Html。 |
| resolver | IExternalResourceResolver | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

追加されたスライド。

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlText | String | 追加する Html。 |

### 戻り値

追加されたスライド

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlReader | TextReader | HTML ファイルのソースとして使用される TextReader オブジェクト。 |
| resolver | IExternalResourceResolver | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

追加されたスライド。

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlReader | TextReader | HTML ファイルのソースとして使用される TextReader オブジェクト。 |

### 戻り値

追加されたスライド

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlStream | Stream | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | IExternalResourceResolver | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | String | 指定された HTML の URI。相対リンクの解決に使用されます。 |

### 戻り値

追加されたスライド。

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlStream | Stream | HTML ファイルのソースとして使用される Stream オブジェクト。 |

### 戻り値

追加されたスライド

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlText | String | 追加する Html。 |
| useSlideWithIndexAsStart | Boolean | 挿入開始方法を決定するフラグです。新しいスライドから開始するか、指定されたインデックスのスライドから開始するかです。**true** の場合、データ挿入は指定されたインデックスのスライド上の空白から開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

追加されたスライド

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlText | String | 追加する Html。 |
| resolver | IExternalResourceResolver | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | String | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | Boolean | 挿入開始方法を決定するフラグです。新しいスライドから開始するか、指定されたインデックスのスライドから開始するかです。**true** の場合、データ挿入は指定されたインデックスのスライド上の空白から開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

追加されたスライド。

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlStream | Stream | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| useSlideWithIndexAsStart | Boolean | 挿入開始方法を決定するフラグです。新しいスライドから開始するか、指定されたインデックスのスライドから開始するかです。**true** の場合、データ挿入は指定されたインデックスのスライド上の空白から開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

追加されたスライド

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

HTML テキストからスライドを作成し、指定された位置にコレクションへ挿入します。

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | 挿入位置。 |
| htmlStream | Stream | HTML ファイルのソースとして使用される Stream オブジェクト。 |
| resolver | IExternalResourceResolver | 外部オブジェクトを取得するために使用されるコールバックオブジェクト。このパラメーターが null の場合、すべての外部オブジェクトは無視されます。 |
| uri | String | 指定された HTML の URI。相対リンクの解決に使用されます。 |
| useSlideWithIndexAsStart | Boolean | 挿入開始方法を決定するフラグです。新しいスライドから開始するか、指定されたインデックスのスライドから開始するかです。**true** の場合、データ挿入は指定されたインデックスのスライド上の空白から開始されます。**false** の場合、データは作成されたスライドに追加されます。 |

### 戻り値

追加されたスライド。

### 参照

* インターフェイス [ISlide](../../islide)
* インターフェイス [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* インターフェイス [ISlideCollection](../../islidecollection)
* 名前空間 [Aspose.Slides](../../islidecollection)
* アセンブリ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->