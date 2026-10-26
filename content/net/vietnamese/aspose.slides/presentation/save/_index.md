---
title: Save
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Lưu tất cả các slide của một bài thuyết trình vào một tệp với định dạng đã chỉ định.
type: docs
weight: 390
url: /vi/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Lưu tất cả các slide của một bài thuyết trình vào một tệp với định dạng đã chỉ định.

```csharp
public void Save(string fname, SaveFormat format)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | String | Đường dẫn tới tệp đã tạo. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |

### Xem Thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Lưu tất cả các slide của một bài thuyết trình vào một luồng với định dạng đã chỉ định.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | Stream | Luồng đầu ra. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |

### Xem Thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### Xem Thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Lưu tất cả các slide của một bài thuyết trình vào một luồng với định dạng đã chỉ định và các tùy chọn bổ sung.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | Stream | Luồng đầu ra. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |
| options | ISaveOptions | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| Ngoại lệ | Điều kiện |
| --- | --- |
| NotSupportedException | Nếu bạn cố gắng lưu tệp được mã hóa ở định dạng không phải Office 2007-2010 |

### Xem Thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Lưu tất cả các slide của một bài thuyết trình thành một tập hợp các tệp đại diện cho markup XAML.

```csharp
public void Save(IXamlOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | IXamlOptions | Các tùy chọn định dạng XAML. |

### Ví dụ

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Xem Thêm

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Lưu các slide được chỉ định của một bài thuyết trình vào một tệp với định dạng đã chỉ định, giữ nguyên số trang.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | String | Đường dẫn tới tệp đã tạo. |
| slides | Int32[] | Mảng các vị trí slide, bắt đầu từ 1. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |

### Ngoại lệ

| Ngoại lệ | Điều kiện |
| --- | --- |
| ArgumentNullException | Khi tham số stream hoặc slides là null. |
| ArgumentOutOfRangeException | Khi tham số slides chứa số trang không đúng. |
| InvalidOperationException | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Xem Thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Lưu các slide được chỉ định của một bài thuyết trình vào một tệp với định dạng đã chỉ định, giữ nguyên số trang.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | String | Đường dẫn tới tệp đã tạo. |
| slides | Int32[] | Mảng các vị trí slide, bắt đầu từ 1. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |
| options | ISaveOptions | Các tùy chọn định dạng bổ sung. |

### Xem Thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Lưu các slide được chỉ định của một bài thuyết trình vào một luồng với định dạng đã chỉ định, giữ nguyên số trang.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | Stream | Luồng đầu ra. |
| slides | Int32[] | Mảng các vị trí slide, bắt đầu từ 1. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |

### Xem Thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Lưu các slide được chỉ định của một bài thuyết trình vào một luồng với định dạng đã chỉ định, giữ nguyên số trang.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | Stream | Luồng đầu ra. |
| slides | Int32[] | Mảng các vị trí slide, bắt đầu từ 1. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |
| options | ISaveOptions | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| Ngoại lệ | Điều kiện |
| --- | --- |
| ArgumentNullException | Khi tham số stream hoặc slides là null. |
| ArgumentOutOfRangeException | Khi tham số slides chứa số trang không đúng. |
| InvalidOperationException | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ví dụ

Ví dụ sau đây cho thấy cách chuyển đổi PowerPoint sang PNG.

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

Ví dụ sau đây cho thấy cách chuyển đổi PowerPoint sang PNG với kích thước tùy chỉnh.

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

Ví dụ sau đây cho thấy cách chuyển đổi PowerPoint sang PNG với kích thước tùy chỉnh.

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

### Xem Thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->