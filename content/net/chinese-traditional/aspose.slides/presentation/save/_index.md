---
title: Save
second_title: Aspose.Sildes for .NET API 參考文件
description: 將簡報的所有投影片儲存為具有指定格式的檔案。
type: docs
weight: 390
url: /zh-hant/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

將簡報的所有投影片儲存為指定格式的檔案。

```csharp
public void Save(string fname, SaveFormat format)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | String | 要建立的檔案路徑。 |
| format | SaveFormat | 匯出資料的格式。 |

### 另請參閱

* 列舉 [SaveFormat](../../../aspose.slides.export/saveformat)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 程式集 [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

將簡報的所有投影片儲存至指定格式的串流中。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | Stream | 輸出串流。 |
| format | SaveFormat | 匯出資料的格式。 |

### 另請參閱

* 列舉 [SaveFormat](../../../aspose.slides.export/saveformat)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 程式集 [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### 另請參閱

* 列舉 [SaveFormat](../../../aspose.slides.export/saveformat)
* 介面 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 程式集 [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

將簡報的所有投影片儲存至指定格式的串流中，並使用其他選項。

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | Stream | 輸出串流。 |
| format | SaveFormat | 匯出資料的格式。 |
| options | ISaveOptions | 其他格式選項。 |

### 例外

| 例外 | 條件 |
| --- | --- |
| NotSupportedException | 若嘗試以非 Office 2007-2010 格式儲存加密檔案 |

### 另請參閱

* 列舉 [SaveFormat](../../../aspose.slides.export/saveformat)
* 介面 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 程式集 [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

將簡報的所有投影片儲存為一組代表 XAML 標記的檔案。

```csharp
public void Save(IXamlOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | IXamlOptions | XAML 格式的選項。 |

### 範例

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### 另請參閱

* 介面 [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 程式集 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

將簡報中指定的投影片以保留頁碼的方式儲存為指定格式的檔案。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | String | 要建立的檔案路徑。 |
| slides | Int32[] | 投影片位置陣列，從 1 起算。 |
| format | SaveFormat | 匯出資料的格式。 |

### 例外

| 例外 | 條件 |
| --- | --- |
| ArgumentNullException | 當 stream 或 slides 參數為 null 時。 |
| ArgumentOutOfRangeException | 當 slides 參數包含錯誤的頁碼時。 |
| InvalidOperationException | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另請參閱

* 列舉 [SaveFormat](../../../aspose.slides.export/saveformat)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 程式集 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

將簡報中指定的投影片以保留頁碼的方式儲存為指定格式的檔案，並使用其他選項。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fname | String | 要建立的檔案路徑。 |
| slides | Int32[] | 投影片位置陣列，從 1 起算。 |
| format | SaveFormat | 匯出資料的格式。 |
| options | ISaveOptions | 其他格式選項。 |

### 另請參閱

* 列舉 [SaveFormat](../../../aspose.slides.export/saveformat)
* 介面 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 程式集 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

將簡報中指定的投影片以保留頁碼的方式儲存至指定格式的串流中。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | Stream | 輸出串流。 |
| slides | Int32[] | 投影片位置陣列，從 1 起算。 |
| format | SaveFormat | 匯出資料的格式。 |

### 另請參閱

* 列舉 [SaveFormat](../../../aspose.slides.export/saveformat)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 程式集 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

將簡報中指定的投影片以保留頁碼的方式儲存至指定格式的串流中，並使用其他選項。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | Stream | 輸出串流。 |
| slides | Int32[] | 投影片位置陣列，從 1 起算。 |
| format | SaveFormat | 匯出資料的格式。 |
| options | ISaveOptions | 其他格式選項。 |

### 例外

| 例外 | 條件 |
| --- | --- |
| ArgumentNullException | 當 stream 或 slides 參數為 null 時。 |
| ArgumentOutOfRangeException | 當 slides 參數包含錯誤的頁碼時。 |
| InvalidOperationException | 當使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 範例

以下示例說明如何將 PowerPoint 轉換為 PNG。

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

以下示例說明如何使用自訂尺寸將 PowerPoint 轉換為 PNG。

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

以下示例說明如何使用自訂大小將 PowerPoint 轉換為 PNG。

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

* 列舉 [SaveFormat](../../../aspose.slides.export/saveformat)
* 介面 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 類別 [Presentation](../../presentation)
* 命名空間 [Aspose.Slides](../../presentation)
* 程式集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->