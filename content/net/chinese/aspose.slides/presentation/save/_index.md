---
title: 保存
second_title: Aspose.Sildes for .NET API 参考
description: 将指定的演示文稿幻灯片保存到指定格式的文件，保留页码。
type: docs
weight: 380
url: /zh/aspose.slides/presentation/save/
---

## Save(string, int[], SaveFormat) {#save_7}

将指定的演示文稿幻灯片保存到指定格式的文件，保留页码。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建文件的路径。 |
| slides | Int32[] | 包含幻灯片位置的数组，从 1 开始。 |
| format | SaveFormat | 导出数据的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为 null 时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页码时。 |
| InvalidOperationException | 当使用不支持的 SaveFormat 时，例如 PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

将指定的演示文稿幻灯片保存到指定格式的文件，保留页码。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建文件的路径。 |
| slides | Int32[] | 包含幻灯片位置的数组，从 1 开始。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

将指定的演示文稿幻灯片保存到指定格式的流，保留页码。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 包含幻灯片位置的数组，从 1 开始。 |
| format | SaveFormat | 导出数据的格式。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

将指定的演示文稿幻灯片保存到指定格式的流，保留页码。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 包含幻灯片位置的数组，从 1 开始。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当流或幻灯片参数为 null 时。 |
| ArgumentOutOfRangeException | 当幻灯片参数包含错误的页码时。 |
| InvalidOperationException | 当使用不支持的 SaveFormat 时，例如 PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP。 |

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

以下示例展示如何以自定义尺寸将 PowerPoint 转换为 PNG。

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

以下示例展示如何以自定义大小将 PowerPoint 转换为 PNG。

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

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat) {#save_5}

将演示文稿的所有幻灯片保存到指定格式的文件。

```csharp
public void Save(string fname, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建文件的路径。 |
| format | SaveFormat | 导出数据的格式。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

将演示文稿的所有幻灯片保存到指定格式的流。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| format | SaveFormat | 导出数据的格式。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

将演示文稿的所有幻灯片保存到指定格式的流，并附加其他选项。

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
| NotSupportedException | 如果尝试将加密文件保存为非 Office 2007-2010 格式。 |

### 参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

将演示文稿的所有幻灯片保存为表示 XAML 标记的一组文件。

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

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->