---
title: IParagraphCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một tập hợp các đoạn văn.
type: docs
url: /vi/com.aspose.slides/iparagraphcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Biểu diễn một tập hợp các đoạn văn.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [getCount()](#getCount--) | Lấy số lượng phần tử thực sự chứa trong tập hợp. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Thêm một Paragraph vào cuối tập hợp. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Thêm nội dung của ParagraphCollection vào cuối tập hợp. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Chèn một Paragraph vào tập hợp tại chỉ mục được chỉ định. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Chèn nội dung của ParagraphCollection vào tập hợp tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục được chỉ định của tập hợp. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Xóa lần xuất hiện đầu tiên của một đoạn văn cụ thể. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Thêm văn bản từ chuỗi html được chỉ định vào tập hợp. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Thêm văn bản từ chuỗi html được chỉ định vào tập hợp. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Chuyển đổi các đoạn văn được chỉ định sang HTML và trả về dưới dạng đối tượng String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số lượng phần tử thực sự chứa trong tập hợp. int chỉ đọc.

**Giá trị trả về:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Thêm một Paragraph vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph sẽ được thêm vào cuối tập hợp. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Thêm nội dung của ParagraphCollection vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection sẽ được thêm vào cuối tập hợp. |

**Giá trị trả về:**
int - Chỉ mục mà Paragraph đã được thêm vào hoặc -1 nếu không có gì để thêm.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Chèn một Paragraph vào tập hợp tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 mà Paragraph sẽ được chèn vào. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph để chèn. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Chèn nội dung của ParagraphCollection vào tập hợp tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 mà các đoạn văn sẽ được chèn vào. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Các đoạn văn để chèn. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi tập hợp.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục được chỉ định của tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Xóa lần xuất hiện đầu tiên của một đoạn văn cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Đoạn văn cần xóa khỏi tập hợp. |

**Giá trị trả về:**
boolean - true nếu mục được xóa thành công; ngược lại, false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Thêm văn bản từ chuỗi html được chỉ định vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Thêm văn bản từ chuỗi html được chỉ định vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback Resolver, giải quyết URI và lấy các đối tượng được tham chiếu. |
| uri | java.lang.String | URI để thêm tài liệu HTML. Được sử dụng để giải quyết các liên kết tương đối.

--------------------

Việc chỉ định resolver có thể tiềm ẩn lỗ hổng bảo mật. Hãy sử dụng cẩn thận. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Chuyển đổi các đoạn văn được chỉ định sang HTML và trả về dưới dạng đối tượng String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| firstParagraphIndex | int | Chỉ mục đoạn văn đầu tiên (int) |
| paragraphsCount | int | Số lượng đoạn văn (int) |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Tùy chọn chuyển đổi [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Giá trị trả về:**
java.lang.String - HTML được tạo.