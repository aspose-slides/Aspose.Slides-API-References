---
title: Save
second_title: Aspose.Sildes for .NET API 參考
description: 將簡報的所有投影片保存為具有指定格式的檔案。
type: docs
weight: 390
url: /zh-hant/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

將簡報的所有投影片保存為具有指定格式的檔案。

```csharp
public void Save(string fname, SaveFormat format)
```

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fname | String | 建立檔案的路徑。 |
| format | SaveFormat | 匯出資料的格式。 |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

將簡報的所有投影片保存至指定格式的串流。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | Stream | 輸出串流。 |
| format | SaveFormat | 匯出資料的格式。 |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

將簡報的所有投影片保存為具有指定格式且附加選項的檔案。

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fname | String | 建立檔案的路徑。 |
| format | SaveFormat | 匯出資料的格式。 |
| options | ISaveOptions | 其他格式選項。 |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

將簡報的所有投影片保存至具有指定格式且附加選項的串流。

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | Stream | 輸出串流。 |
| format | SaveFormat | 匯出資料的格式。 |
| options | ISaveOptions | 其他格式選項。 |

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| NotSupportedException | 若嘗試以非 Office 2007-2010 格式保存已加密檔案 |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

將簡報中指定的投影片保存為具有指定格式的檔案。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fname | String | 建立檔案的路徑。 |
| slides | Int32[] | 包含投影片位置的陣列，從 1 開始。 |
| format | SaveFormat | 匯出資料的格式。 |

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| ArgumentNullException | 當 stream 或 slides 參數為 null 時。 |
| ArgumentOutOfRangeException | 當 slides 參數包含錯誤的頁碼時。 |
| InvalidOperationException | 使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

將簡報中指定的投影片保存為具有指定格式且附加選項的檔案。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fname | String | 建立檔案的路徑。 |
| slides | Int32[] | 包含投影片位置的陣列，從 1 開始。 |
| format | SaveFormat | 匯出資料的格式。 |
| options | ISaveOptions | 其他格式選項。 |

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| ArgumentNullException | 當 stream 或 slides 參數為 null 時。 |
| ArgumentOutOfRangeException | 當 slides 參數包含錯誤的頁碼時。 |
| InvalidOperationException | 使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

將簡報中指定的投影片保存至具有指定格式的串流。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | Stream | 輸出串流。 |
| slides | Int32[] | 包含投影片位置的陣列，從 1 開始。 |
| format | SaveFormat | 匯出資料的格式。 |

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| ArgumentNullException | 當 stream 或 slides 參數為 null 時。 |
| ArgumentOutOfRangeException | 當 slides 參數包含錯誤的頁碼時。 |
| InvalidOperationException | 使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

將簡報中指定的投影片保存至具有指定格式且附加選項的串流。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | Stream | 輸出串流。 |
| slides | Int32[] | 包含投影片位置的陣列，從 1 開始。 |
| format | SaveFormat | 匯出資料的格式。 |
| options | ISaveOptions | 其他格式選項。 |

### 例外狀況

| 例外 | 條件 |
| --- | --- |
| ArgumentNullException | 當 stream 或 slides 參數為 null 時。 |
| ArgumentOutOfRangeException | 當 slides 參數包含錯誤的頁碼時。 |
| InvalidOperationException | 使用不支援的 SaveFormat 時，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另請參閱

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

將簡報的所有投影片保存為一組代表 XAML 標記的檔案。

```csharp
public void Save(IXamlOptions options)
```

| 參數 | 型別 | 說明 |
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

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->