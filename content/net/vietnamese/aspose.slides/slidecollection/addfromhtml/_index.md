---
title: AddFromHtml
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.
type: docs
weight: 70
url: /vi/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlText | String | Html để thêm. |
| resolver | IExternalResourceResolver | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | String | Một URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

### Giá trị trả về

Các slide đã thêm.

### Xem thêm

* giao diện [ISlide](../../islide)
* giao diện [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlText | String | Html để thêm. |

### Giá trị trả về

Các slide đã thêm

### Xem thêm

* giao diện [ISlide](../../islide)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlReader | TextReader | Đối tượng TextReader sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | IExternalResourceResolver | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | String | Một URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

### Giá trị trả về

Các slide đã thêm.

### Xem thêm

* giao diện [ISlide](../../islide)
* giao diện [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlReader | TextReader | Đối tượng TextReader sẽ được sử dụng làm nguồn của tệp HTML. |

### Giá trị trả về

Các slide đã thêm

### Xem thêm

* giao diện [ISlide](../../islide)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlStream | Stream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | IExternalResourceResolver | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này là null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | String | Một URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

### Giá trị trả về

Các slide đã thêm.

### Xem thêm

* giao diện [ISlide](../../islide)
* giao diện [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Tạo các slide từ văn bản HTML và thêm chúng vào cuối bộ sưu tập.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| htmlStream | Stream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |

### Giá trị trả về

Các slide đã thêm

### Ví dụ

```csharp
[C#]
// Tạo một thể hiện của lớp Presentation.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// Gọi phương thức AddFromHtml và truyền tệp HTML.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Sử dụng phương thức Save để lưu tệp dưới dạng tài liệu PowerPoint.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [ISlide](../../islide)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->