---
title: InsertFromHtml
second_title: Aspose.Sildes cho .NET API Reference
description: Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.
type: docs
weight: 140
url: /vi/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlText | String | Html cần thêm. |
| resolver | IExternalResourceResolver | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

### Giá trị trả về

Các slide được thêm.

### Xem thêm

* giao diện [ISlide](../../islide)
* giao diện [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlText | String | Html cần thêm. |
| resolver | IExternalResourceResolver | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |
| useSlideWithIndexAsStart | Boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ số đã chỉ định. Nếu **true**, việc chèn dữ liệu sẽ bắt đầu từ một không gian trống trên slide có chỉ số đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide đã tạo. |

### Giá trị trả về

Các slide được thêm.

### Xem thêm

* giao diện [ISlide](../../islide)
* giao diện [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlText | String | Html cần thêm. |

### Giá trị trả về

Các slide được thêm

### Xem thêm

* giao diện [ISlide](../../islide)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlText | String | Html cần thêm. |
| useSlideWithIndexAsStart | Boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ số đã chỉ định. Nếu **true**, việc chèn dữ liệu sẽ bắt đầu từ một không gian trống trên slide có chỉ số đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide đã tạo. |

### Giá trị trả về

Các slide được thêm

### Xem thêm

* giao diện [ISlide](../../islide)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlReader | TextReader | Đối tượng TextReader sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | IExternalResourceResolver | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

### Giá trị trả về

Các slide được thêm.

### Xem thêm

* giao diện [ISlide](../../islide)
* giao diện [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlReader | TextReader | Đối tượng TextReader sẽ được sử dụng làm nguồn của tệp HTML. |

### Giá trị trả về

Các slide được thêm

### Xem thêm

* giao diện [ISlide](../../islide)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlStream | Stream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | IExternalResourceResolver | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |

### Giá trị trả về

Các slide được thêm.

### Xem thêm

* giao diện [ISlide](../../islide)
* giao diện [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlStream | Stream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| resolver | IExternalResourceResolver | Đối tượng callback được sử dụng để lấy các đối tượng bên ngoài. Nếu tham số này null, tất cả các đối tượng bên ngoài sẽ bị bỏ qua. |
| uri | String | URI của HTML đã chỉ định. Được sử dụng để giải quyết các liên kết tương đối. |
| useSlideWithIndexAsStart | Boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ số đã chỉ định. Nếu **true**, việc chèn dữ liệu sẽ bắt đầu từ một không gian trống trên slide có chỉ số đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide đã tạo. |

### Giá trị trả về

Các slide được thêm.

### Xem thêm

* giao diện [ISlide](../../islide)
* giao diện [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlStream | Stream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |

### Giá trị trả về

Các slide được thêm

### Xem thêm

* giao diện [ISlide](../../islide)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Tạo các slide từ văn bản HTML và chèn chúng vào bộ sưu tập tại vị trí được chỉ định.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | Int32 | Vị trí để chèn. |
| htmlStream | Stream | Đối tượng Stream sẽ được sử dụng làm nguồn của tệp HTML. |
| useSlideWithIndexAsStart | Boolean | Cờ này xác định cách bắt đầu chèn: từ một slide mới hoặc từ slide có chỉ số đã chỉ định. Nếu **true**, việc chèn dữ liệu sẽ bắt đầu từ một không gian trống trên slide có chỉ số đã chỉ định. Nếu **false**, dữ liệu sẽ được thêm vào các slide đã tạo. |

### Giá trị trả về

Các slide được thêm

### Xem thêm

* giao diện [ISlide](../../islide)
* lớp [SlideCollection](../../slidecollection)
* không gian tên [Aspose.Slides](../../slidecollection)
* tập hợp [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->