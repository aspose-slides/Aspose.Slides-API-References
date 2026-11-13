---
title: Save
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーションのすべてのスライドを、指定された形式でファイルに保存します。
type: docs
weight: 390
url: /ja/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

プレゼンテーションのすべてのスライドを、指定された形式でファイルに保存します。

```csharp
public void Save(string fname, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | 作成されたファイルへのパス。 |
| format | SaveFormat | エクスポートデータの形式。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

プレゼンテーションのすべてのスライドを、指定された形式でストリームに保存します。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | 出力ストリーム。 |
| format | SaveFormat | エクスポートデータの形式。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

プレゼンテーションのすべてのスライドを、指定された形式でファイルに保存し、追加オプションを適用します。

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | 作成されたファイルへのパス。 |
| format | SaveFormat | エクスポートデータの形式。 |
| options | ISaveOptions | 追加のフォーマットオプション。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

プレゼンテーションのすべてのスライドを、指定された形式でストリームに保存し、追加オプションを適用します。

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | 出力ストリーム。 |
| format | SaveFormat | エクスポートデータの形式。 |
| options | ISaveOptions | 追加のフォーマットオプション。 |

### 例外

| exception | condition |
| --- | --- |
| NotSupportedException | 暗号化されたファイルを Office 2007-2010 形式以外で保存しようとした場合 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

プレゼンテーションの指定されたスライドを、指定された形式でファイルに保存します。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | 作成されたファイルへのパス。 |
| slides | Int32[] | スライド位置の配列（1 から開始）。 |
| format | SaveFormat | エクスポートデータの形式。 |

### 例外

| exception | condition |
| --- | --- |
| ArgumentNullException | ストリームまたは slides パラメーターが null の場合。 |
| ArgumentOutOfRangeException | slides パラメーターに無効なページ番号が含まれている場合。 |
| InvalidOperationException | サポートされていない SaveFormat が使用された場合（例：PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP）。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

プレゼンテーションの指定されたスライドを、指定された形式でファイルに保存し、追加オプションを適用します。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fname | String | 作成されたファイルへのパス。 |
| slides | Int32[] | スライド位置の配列（1 から開始）。 |
| format | SaveFormat | エクスポートデータの形式。 |
| options | ISaveOptions | 追加のフォーマットオプション。 |

### 例外

| exception | condition |
| --- | --- |
| ArgumentNullException | ストリームまたは slides パラメーターが null の場合。 |
| ArgumentOutOfRangeException | slides パラメーターに無効なページ番号が含まれている場合。 |
| InvalidOperationException | サポートされていない SaveFormat が使用された場合（例：PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP）。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

プレゼンテーションの指定されたスライドを、指定された形式でストリームに保存します。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | 出力ストリーム。 |
| slides | Int32[] | スライド位置の配列（1 から開始）。 |
| format | SaveFormat | エクスポートデータの形式。 |

### 例外

| exception | condition |
| --- | --- |
| ArgumentNullException | ストリームまたは slides パラメーターが null の場合。 |
| ArgumentOutOfRangeException | slides パラメーターに無効なページ番号が含まれている場合。 |
| InvalidOperationException | サポートされていない SaveFormat が使用された場合（例：PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP）。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

プレゼンテーションの指定されたスライドを、指定された形式でストリームに保存し、追加オプションを適用します。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | 出力ストリーム。 |
| slides | Int32[] | スライド位置の配列（1 から開始）。 |
| format | SaveFormat | エクスポートデータの形式。 |
| options | ISaveOptions | 追加のフォーマットオプション。 |

### 例外

| exception | condition |
| --- | --- |
| ArgumentNullException | ストリームまたは slides パラメーターが null の場合。 |
| ArgumentOutOfRangeException | slides パラメーターに無効なページ番号が含まれている場合。 |
| InvalidOperationException | サポートされていない SaveFormat が使用された場合（例：PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP）。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

プレゼンテーションのすべてのスライドを XAML マークアップを表す一連のファイルに保存します。

```csharp
public void Save(IXamlOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | IXamlOptions | XAML フォーマットオプション。 |

### 例

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### 参照

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->