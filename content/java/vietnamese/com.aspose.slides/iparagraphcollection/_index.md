---
title: IParagraphCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đ đại diện cho một bộ sưu tập các đoạn văn.
type: docs
url: /vi/com.aspose.slides/iparagraphcollection/
---
**Tất cả các giao diện được triển khai:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)  
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Đại diện cho một bộ sưu tập các paragraph.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [getCount()](#getCount--) | Lấy số lượng phần tử thực sự chứa trong bộ sưu tập. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Thêm một Paragraph vào cuối bộ sưu tập. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Thêm nội dung của ParagraphCollection vào cuối bộ sưu tập. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Chèn một Paragraph vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Chèn nội dung của ParagraphCollection vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định trong bộ sưu tập. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Xóa lần xuất hiện đầu tiên của một paragraph cụ thể. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Thêm văn bản từ chuỗi html đã chỉ định vào bộ sưu tập. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Thêm văn bản từ chuỗi html đã chỉ định vào bộ sưu tập. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Chuyển các paragraph được chỉ định sang HTML và trả về dưới dạng đối tượng String. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IParagraph](../../com.aspose.slides/iparagraph)

### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số lượng phần tử thực sự chứa trong bộ sưu tập. int chỉ đọc.

**Trả về:**
int

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Thêm một Paragraph vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph sẽ được thêm vào cuối bộ sưu tập. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Thêm nội dung của ParagraphCollection vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection sẽ được thêm vào cuối bộ sưu tập. |

**Trả về:**
int - Chỉ mục mà Paragraph đã được thêm vào hoặc -1 nếu không có gì để thêm.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Chèn một Paragraph vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên zero nơi Paragraph sẽ được chèn. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph để chèn. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Chèn nội dung của ParagraphCollection vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên zero nơi các paragraph sẽ được chèn. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Các paragraph để chèn. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên zero của phần tử cần xóa. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Xóa lần xuất hiện đầu tiên của một paragraph cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | paragraph cần xóa khỏi bộ sưu tập. |

**Trả về:**
boolean - true nếu mục đã được xóa thành công; ngược lại, false.

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Thêm văn bản từ chuỗi html đã chỉ định vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Thêm văn bản từ chuỗi html đã chỉ định vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback Resolver giúp giải quyết URI và lấy các đối tượng được tham chiếu. |
| uri | java.lang.String | URI để thêm tài liệu HTML. Được dùng để giải quyết các liên kết tương đối.

--------------------

Việc chỉ định resolver có thể tiềm ẩn lỗ hổng bảo mật. Hãy sử dụng cẩn thận. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Chuyển các paragraph được chỉ định sang HTML và trả về dưới dạng đối tượng String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| firstParagraphIndex | int | Chỉ mục paragraph đầu tiên int |
| paragraphsCount | int | Số lượng paragraph int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Các tùy chọn chuyển đổi [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Trả về:**
java.lang.String - HTML đã tạo.