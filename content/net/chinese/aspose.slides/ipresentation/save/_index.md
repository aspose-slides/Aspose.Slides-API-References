---
title: 保存
second_title: Aspose.Slides for .NET API 参考
description: 将演示文稿的所有幻灯片保存到具有指定格式的文件中。
type: docs
weight: 370
url: /zh/aspose.slides/ipresentation/save/
---

## Save(string, SaveFormat) {#save_5}

将演示文稿的所有幻灯片保存到具有指定格式的文件中。

```csharp
public void Save(string fname, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件的路径。 |
| format | SaveFormat | 导出数据的格式。 |

### 另见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

将演示文稿的所有幻灯片保存到具有指定格式的流中。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| format | SaveFormat | 导出数据的格式。 |

### 另见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

将演示文稿的所有幻灯片保存到具有指定格式和附加选项的文件中。

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件的路径。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 另见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

将演示文稿的所有幻灯片保存到具有指定格式和附加选项的流中。

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非Office 2007-2010格式保存加密文件 |

### 另见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

将演示文稿的指定幻灯片保存到具有指定格式的文件中。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件的路径。 |
| slides | Int32[] | 幻灯片位置的数组，从1开始。 |
| format | SaveFormat | 导出数据的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为null时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页面编号时。 |
| InvalidOperationException | 当使用不支持的SaveFormat时，例如PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

将演示文稿的指定幻灯片保存到具有指定格式的文件中。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件的路径。 |
| slides | Int32[] | 幻灯片位置的数组，从1开始。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为null时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页面编号时。 |
| InvalidOperationException | 当使用不支持的SaveFormat时，例如PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

将演示文稿的指定幻灯片保存到具有指定格式的流中。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 幻灯片位置的数组，从1开始。 |
| format | SaveFormat | 导出数据的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为null时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页面编号时。 |
| InvalidOperationException | 当使用不支持的SaveFormat时，例如PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

将演示文稿的指定幻灯片保存到具有指定格式的流中。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 幻灯片位置的数组，从1开始。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为null时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页面编号时。 |
| InvalidOperationException | 当使用不支持的SaveFormat时，例如PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

将演示文稿的所有幻灯片保存为表示XAML标记的一组文件。

```csharp
public void Save(IXamlOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | IXamlOptions | XAML格式选项。 |

### 示例

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### 另见

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->