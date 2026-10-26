---
title: Save
second_title: Aspose.Sildes for .NET API リファレンス
description: 指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。
type: docs
weight: 380
url: /ja/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。

```csharp
public void Save(string fname, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### 参照

* 列挙型 [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [IPresentation](../../ipresentation)
* 名前空間 [Aspose.Slides](../../ipresentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### 参照

* 列挙型 [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [IPresentation](../../ipresentation)
* 名前空間 [Aspose.Slides](../../ipresentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

指定された形式と追加オプションでプレゼンテーションのすべてのスライドをファイルに保存します。

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 参照

* 列挙型 [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* インターフェイス [IPresentation](../../ipresentation)
* 名前空間 [Aspose.Slides](../../ipresentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

指定された形式と追加オプションでプレゼンテーションのすべてのスライドをストリームに保存します。

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 例外

| 例外 | 条件 |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### 参照

* 列挙型 [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* インターフェイス [IPresentation](../../ipresentation)
* 名前空間 [Aspose.Slides](../../ipresentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

指定された形式でプレゼンテーションの指定したスライドをファイルに保存します。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 参照

* 列挙型 [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [IPresentation](../../ipresentation)
* 名前空間 [Aspose.Slides](../../ipresentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

指定された形式と追加オプションでプレゼンテーションの指定したスライドをファイルに保存します。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 参照

* 列挙型 [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* インターフェイス [IPresentation](../../ipresentation)
* 名前空間 [Aspose.Slides](../../ipresentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

指定された形式でプレゼンテーションの指定したスライドをストリームに保存します。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 参照

* 列挙型 [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [IPresentation](../../ipresentation)
* 名前空間 [Aspose.Slides](../../ipresentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

指定された形式と追加オプションでプレゼンテーションの指定したスライドをストリームに保存します。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 参照

* 列挙型 [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* インターフェイス [IPresentation](../../ipresentation)
* 名前空間 [Aspose.Slides](../../ipresentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

プレゼンテーションのすべてのスライドを XAML マークアップを表す一連のファイルに保存します。

```csharp
public void Save(IXamlOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | IXamlOptions | The XAML format options. |

### 例

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### 参照

* インターフェイス [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* インターフェイス [IPresentation](../../ipresentation)
* 名前空間 [Aspose.Slides](../../ipresentation)
* アセンブリ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->