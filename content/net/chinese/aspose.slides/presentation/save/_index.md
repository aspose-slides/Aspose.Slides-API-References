---
title: Save
second_title: Aspose.Sildes for .NET API 参考
description: 将演示文稿的所有幻灯片保存为具有指定格式的文件。
type: docs
weight: 400
url: /zh/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

将演示文稿的所有幻灯片保存到指定格式的文件中。

```csharp
public void Save(string fname, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件的路径。 |
| format | SaveFormat | 导出数据的格式。 |

### 另见

* 枚举 [SaveFormat](../../../aspose.slides.export/saveformat)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
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

### 另见

* 枚举 [SaveFormat](../../../aspose.slides.export/saveformat)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### 另见

* 枚举 [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

将演示文稿的所有幻灯片保存到指定格式的流中，并使用附加选项。

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加的格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

### 另见

* 枚举 [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
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

### 另见

* 接口 [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

将演示文稿中指定的幻灯片保存到具有指定格式并保留页码的文件中。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件的路径。 |
| slides | Int32[] | 数组，包含幻灯片位置，从 1 开始。 |
| format | SaveFormat | 导出数据的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 stream 或 slides 参数为 null 时。 |
| ArgumentOutOfRangeException | 当 slides 参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另见

* 枚举 [SaveFormat](../../../aspose.slides.export/saveformat)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

将演示文稿中指定的幻灯片保存到具有指定格式并保留页码的文件中。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件的路径。 |
| slides | Int32[] | 数组，包含幻灯片位置，从 1 开始。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加的格式选项。 |

### 另见

* 枚举 [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

将演示文稿中指定的幻灯片保存到具有指定格式并保留页码的流中。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 数组，包含幻灯片位置，从 1 开始。 |
| format | SaveFormat | 导出数据的格式。 |

### 另见

* 枚举 [SaveFormat](../../../aspose.slides.export/saveformat)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
* 程序集 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

将演示文稿中指定的幻灯片保存到具有指定格式并保留页码的流中。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 数组，包含幻灯片位置，从 1 开始。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加的格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 stream 或 slides 参数为 null 时。 |
| ArgumentOutOfRangeException | 当 slides 参数包含错误的页码时。 |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 示例

以下示例展示如何将 PowerPoint 转换为 PNG。

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

以下示例展示如何在自定义尺寸下将 PowerPoint 转换为 PNG。

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

以下示例展示如何在自定义大小下将 PowerPoint 转换为 PNG。

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

### 另见

* 枚举 [SaveFormat](../../../aspose.slides.export/saveformat)
* 接口 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 类 [Presentation](../../presentation)
* 命名空间 [Aspose.Slides](../../presentation)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->