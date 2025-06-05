---
title: Save
second_title: Aspose.Sildes for .NET API Reference
description: 将演示文稿的指定幻灯片保存到具有指定格式的文件，并保持页码。
type: docs
weight: 380
url: /zh/aspose.slides/presentation/save/
---

## Save(string, int[], SaveFormat) {#save_7}

将演示文稿的指定幻灯片保存到具有指定格式的文件，并保持页码。

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | Int32[] | 从1开始的幻灯片位置数组。 |
| format | SaveFormat | 导出数据的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当stream或slides参数为null时。 |
| ArgumentOutOfRangeException | 当slides参数包含错误的页码时。 |
| InvalidOperationException | 当使用不支持的SaveFormat时，例如PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另请参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

将演示文稿的指定幻灯片保存到具有指定格式的文件，并保持页码。

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | Int32[] | 从1开始的幻灯片位置数组。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 另请参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

将演示文稿的指定幻灯片保存到流中的指定格式，并保持页码。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 从1开始的幻灯片位置数组。 |
| format | SaveFormat | 导出数据的格式。 |

### 另请参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

将演示文稿的指定幻灯片保存到流中的指定格式，并保持页码。

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| slides | Int32[] | 从1开始的幻灯片位置数组。 |
| format | SaveFormat | 导出数据的格式。 |
| options | ISaveOptions | 附加格式选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当stream或slides参数为null时。 |
| ArgumentOutOfRangeException | 当slides参数包含错误的页码时。 |
| InvalidOperationException | 当使用不支持的SaveFormat时，例如PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 示例

以下示例展示了如何将PowerPoint转换为PNG。

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

以下示例展示了如何将PowerPoint转换为具有自定义尺寸的PNG。

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

以下示例展示了如何将PowerPoint转换为具有自定义大小的PNG。

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

### 另请参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat) {#save_5}

将所有幻灯片保存到具有指定格式的文件。

```csharp
public void Save(string fname, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | SaveFormat | 导出数据的格式。 |

### 另请参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

将所有幻灯片保存到流中的指定格式。

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输出流。 |
| format | SaveFormat | 导出数据的格式。 |

### 另请参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### 另请参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

将所有幻灯片保存到流中的指定格式并附加选项。

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

### 另请参见

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

将所有幻灯片保存到表示XAML标记的一组文件。

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

### 另请参见

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->