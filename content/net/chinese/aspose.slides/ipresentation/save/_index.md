---
title: Save
second_title: Aspose.Slides for .NET API 参考
description: 将演示文稿的所有幻灯片保存到具有指定格式的文件中
type: docs
weight: 340
url: /zh/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

将演示文稿的所有幻灯片保存到具有指定格式的文件中。

```csharp
public void Save(string fname, SaveFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建文件的路径。 |
| format | SaveFormat | 导出数据的格式。 |

### 也可以看看

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 部件 [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

将演示文稿的所有幻灯片以指定格式保存到流中。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| format | SaveFormat | 导出数据的格式。 |

### 也可以看看

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 部件 [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

将演示文稿的所有幻灯片保存到具有指定格式和附加选项的文件中。

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建文件的路径。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 也可以看看

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 部件 [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

以指定格式和附加选项将演示文稿的所有幻灯片保存到流中。

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| NotSupportedException | 如果您尝试将加密文件保存为 无 Office 2007-2010 格式 |

### 也可以看看

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 部件 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

将演示文稿的指定幻灯片保存到具有指定格式的文件中。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建文件的路径。 |
| slides | Int32[] | 包含幻灯片位置的数组，从 1 开始。 |
| format | SaveFormat | 导出数据的格式. |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为空时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 也可以看看

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 部件 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

将演示文稿的指定幻灯片保存到具有指定格式的文件中。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建文件的路径。 |
| slides | Int32[] | 包含幻灯片位置的数组，从 1 开始。 |
| format | SaveFormat | 导出数据的格式. |
| options | ISaveOptions | 附加格式选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为空时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 也可以看看

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 部件 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

将演示文稿的指定幻灯片以指定格式保存到流中。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 包含幻灯片位置的数组，从 1 开始。 |
| format | SaveFormat | 导出数据的格式. |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为空时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 也可以看看

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 部件 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

将演示文稿的指定幻灯片以指定格式保存到流中。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 包含幻灯片位置的数组，从 1 开始。 |
| format | SaveFormat | 导出数据的格式. |
| options | ISaveOptions | 附加格式选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为空时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 也可以看看

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 部件 [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

将演示文稿的所有幻灯片保存到一组表示 XAML 标记的文件中。

```csharp
public void Save(IXamlOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | IXamlOptions | XAML 格式选项。 |

### 例子

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### 也可以看看

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* 命名空间 [Aspose.Slides](../../ipresentation)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
