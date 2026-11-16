---
title: Save
second_title: Aspose.Sildes .NET API 参考
description: 将演示文稿的所有幻灯片保存为具有指定格式的文件。
type: docs
weight: 390
url: /zh/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

将演示文稿的所有幻灯片保存为具有指定格式的文件。

```csharp
public void Save(string fname, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | SaveFormat | 导出数据的格式。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

将演示文稿的所有幻灯片保存到指定格式的流中。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| format | SaveFormat | 导出数据的格式。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

将演示文稿的所有幻灯片保存为具有指定格式并附加选项的文件。

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

将演示文稿的所有幻灯片保存到指定格式并附加选项的流中。

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
| NotSupportedException | 当尝试以非 Office 2007-2010 格式保存加密文件时 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

将演示文稿的指定幻灯片保存为具有指定格式的文件。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | Int32[] | 幻灯片位置数组，从 1 开始计数。 |
| format | SaveFormat | 导出数据的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 stream 或 slides 参数为 null 时。 |
| ArgumentOutOfRangeException | 当 slides 参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

将演示文稿的指定幻灯片保存为具有指定格式的文件。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | Int32[] | 幻灯片位置数组，从 1 开始计数。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 stream 或 slides 参数为 null 时。 |
| ArgumentOutOfRangeException | 当 slides 参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

将演示文稿的指定幻灯片保存到指定格式的流中。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 幻灯片位置数组，从 1 开始计数。 |
| format | SaveFormat | 导出数据的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 stream 或 slides 参数为 null 时。 |
| ArgumentOutOfRangeException | 当 slides 参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

将演示文稿的指定幻灯片保存到指定格式并附加选项的流中。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 幻灯片位置数组，从 1 开始计数。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 stream 或 slides 参数为 null 时。 |
| ArgumentOutOfRangeException | 当 slides 参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

将演示文稿的所有幻灯片保存为一组表示 XAML 标记的文件。

```csharp
public void Save(IXamlOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | IXamlOptions | XAML 格式选项。 |

### 示例

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### 参见

* 接口 [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* 接口 [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->