---
title: Save
second_title: Aspose.Sildes for .NET API リファレンス
description: 指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。
type: docs
weight: 390
url: /ja/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。

```csharp
public void Save(string fname, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fname | String | 作成されるファイルへのパス。 |
| format | SaveFormat | エクスポートデータの形式。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | 出力ストリーム。 |
| format | SaveFormat | エクスポートデータの形式。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

指定された形式でプレゼンテーションのすべてのスライドをストリームに保存し、追加オプションを適用します。

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | 出力ストリーム。 |
| format | SaveFormat | エクスポートデータの形式。 |
| options | ISaveOptions | 追加の形式オプション。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| NotSupportedException | Office 2007-2010 形式ではない形式で暗号化されたファイルを保存しようとした場合 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

指定された XAML マークアップを表すファイル群にプレゼンテーションのすべてのスライドを保存します。

```csharp
public void Save(IXamlOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | IXamlOptions | XAML 形式のオプション。 |

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
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

指定された形式でページ番号を保持しながら、プレゼンテーションの特定のスライドをファイルに保存します。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fname | String | 作成されるファイルへのパス。 |
| slides | Int32[] | 1 から始まるスライド位置の配列。 |
| format | SaveFormat | エクスポートデータの形式。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | stream または slides パラメーターが null のとき。 |
| ArgumentOutOfRangeException | slides パラメーターに無効なページ番号が含まれるとき。 |
| InvalidOperationException | PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP など、サポートされていない SaveFormat が使用されたとき。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

指定された形式でページ番号を保持しながら、プレゼンテーションの特定のスライドをファイルに保存し、追加オプションを適用します。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fname | String | 作成されるファイルへのパス。 |
| slides | Int32[] | 1 から始まるスライド位置の配列。 |
| format | SaveFormat | エクスポートデータの形式。 |
| options | ISaveOptions | 追加の形式オプション。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

指定された形式でページ番号を保持しながら、プレゼンテーションの特定のスライドをストリームに保存します。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | 出力ストリーム。 |
| slides | Int32[] | 1 から始まるスライド位置の配列。 |
| format | SaveFormat | エクスポートデータの形式。 |

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

指定された形式でページ番号を保持しながら、プレゼンテーションの特定のスライドをストリームに保存し、追加オプションを適用します。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | 出力ストリーム。 |
| slides | Int32[] | 1 から始まるスライド位置の配列。 |
| format | SaveFormat | エクスポートデータの形式。 |
| options | ISaveOptions | 追加の形式オプション。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | stream または slides パラメーターが null のとき。 |
| ArgumentOutOfRangeException | slides パラメーターに無効なページ番号が含まれるとき。 |
| InvalidOperationException | PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP など、サポートされていない SaveFormat が使用されたとき。 |

### 例

次の例は、PowerPoint を PNG に変換する方法を示しています。

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

次の例は、カスタム寸法で PowerPoint を PNG に変換する方法を示しています。

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

次の例は、カスタムサイズで PowerPoint を PNG に変換する方法を示しています。

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### 参照

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* インターフェイス [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->