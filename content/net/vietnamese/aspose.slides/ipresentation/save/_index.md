---
title: Save
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Lưu tất cả các slide của bài thuyết trình vào một tệp với định dạng được chỉ định.
type: docs
weight: 380
url: /vi/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Lưu tất cả các slide của bài thuyết trình vào một tệp với định dạng được chỉ định.

```csharp
public void Save(string fname, SaveFormat format)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | String | Đường dẫn tới tệp đã tạo. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |

### Xem thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Lưu tất cả các slide của bài thuyết trình vào một luồng ở định dạng được chỉ định.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | Stream | Luồng đầu ra. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |

### Xem thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Lưu tất cả các slide của bài thuyết trình vào một tệp với định dạng được chỉ định và các tùy chọn bổ sung.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | String | Đường dẫn tới tệp đã tạo. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |
| options | ISaveOptions | Các tùy chọn định dạng bổ sung. |

### Xem thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Lưu tất cả các slide của bài thuyết trình vào một luồng ở định dạng được chỉ định và các tùy chọn bổ sung.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | Stream | Luồng đầu ra. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |
| options | ISaveOptions | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| NotSupportedException | Nếu bạn cố gắng lưu tệp đã mã hóa ở định dạng không phải Office 2007-2010 |

### Xem thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Lưu các slide được chỉ định của bài thuyết trình vào một tệp với định dạng được chỉ định.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | String | Đường dẫn tới tệp đã tạo. |
| slides | Int32[] | Mảng chứa vị trí các slide, bắt đầu từ 1. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentNullException | Khi tham số stream hoặc slides có giá trị null. |
| ArgumentOutOfRangeException | Khi tham số slides chứa số trang không hợp lệ. |
| InvalidOperationException | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Xem thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Lưu các slide được chỉ định của bài thuyết trình vào một tệp với định dạng được chỉ định.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fname | String | Đường dẫn tới tệp đã tạo. |
| slides | Int32[] | Mảng chứa vị trí các slide, bắt đầu từ 1. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |
| options | ISaveOptions | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentNullException | Khi tham số stream hoặc slides có giá trị null. |
| ArgumentOutOfRangeException | Khi tham số slides chứa số trang không hợp lệ. |
| InvalidOperationException | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Xem thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Lưu các slide được chỉ định của bài thuyết trình vào một luồng ở định dạng được chỉ định.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | Stream | Luồng đầu ra. |
| slides | Int32[] | Mảng chứa vị trí các slide, bắt đầu từ 1. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentNullException | Khi tham số stream hoặc slides có giá trị null. |
| ArgumentOutOfRangeException | Khi tham số slides chứa số trang không hợp lệ. |
| InvalidOperationException | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Xem thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Lưu các slide được chỉ định của bài thuyết trình vào một luồng ở định dạng được chỉ định.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | Stream | Luồng đầu ra. |
| slides | Int32[] | Mảng chứa vị trí các slide, bắt đầu từ 1. |
| format | SaveFormat | Định dạng của dữ liệu được xuất. |
| options | ISaveOptions | Các tùy chọn định dạng bổ sung. |

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| ArgumentNullException | Khi tham số stream hoặc slides có giá trị null. |
| ArgumentOutOfRangeException | Khi tham số slides chứa số trang không hợp lệ. |
| InvalidOperationException | Khi sử dụng SaveFormat không được hỗ trợ, ví dụ PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Xem thêm

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Lưu tất cả các slide của bài thuyết trình vào một tập hợp các tệp biểu diễn markup XAML.

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

### Xem thêm

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->