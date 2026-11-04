---
title: Save
second_title: Aspose.Sildes for .NET API 參考
description: 將簡報的所有投影片儲存為具有指定格式的檔案。
type: docs
weight: 400
url: /zh-hant/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

將簡報的所有投影片儲存為具有指定格式的檔案。

```csharp
public void Save(string fname, SaveFormat format)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

將簡報的所有投影片儲存為指定格式的串流。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

將簡報的所有投影片儲存為指定格式的串流，並使用其他選項。

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

將簡報的所有投影片儲存為一組表示 XAML 標記的檔案。

```csharp
public void Save(IXamlOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | IXamlOptions | The XAML format options. |

### 範例

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### 另請參閱

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

將簡報中指定的投影片儲存為具有指定格式且保留頁碼的檔案。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

將簡報中指定的投影片儲存為具有指定格式且保留頁碼的檔案。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

將簡報中指定的投影片儲存為具有指定格式且保留頁碼的串流。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

將簡報中指定的投影片儲存為具有指定格式且保留頁碼的串流。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| ArgumentNullException | When stream or slides parameter is null. |
| ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 範例

以下範例示範如何將 PowerPoint 轉換為 PNG。

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

以下範例示範如何將 PowerPoint 轉換為自訂尺寸的 PNG。

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

以下範例示範如何將 PowerPoint 轉換為自訂大小的 PNG。

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

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->