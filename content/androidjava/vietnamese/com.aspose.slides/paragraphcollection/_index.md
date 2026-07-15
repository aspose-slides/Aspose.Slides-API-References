---
title: ParagraphCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho một bộ sưu tập các đoạn văn.
type: docs
url: /vi/com.aspose.slides/paragraphcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Represents a collection of a paragraphs.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCount()](#getCount--) | Lấy số phần tử thực sự chứa trong bộ sưu tập. |
| [isReadOnly()](#isReadOnly--) | Lấy giá trị cho biết liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có phải chỉ đọc hay không. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Thêm một Paragraph vào cuối bộ sưu tập. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Thêm nội dung của ParagraphCollection vào cuối bộ sưu tập. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Xác định chỉ mục của một mục cụ thể trong List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Chèn một Paragraph vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Chèn nội dung của ParagraphCollection vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Xác định liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một Mảng, bắt đầu tại một chỉ mục Mảng cụ thể. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã chỉ định của bộ sưu tập. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [getSlide()](#getSlide--) | Trả về slide cha của một bộ sưu tập các đoạn văn. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một bộ sưu tập các đoạn văn. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Thêm văn bản từ chuỗi html được chỉ định vào bộ sưu tập. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Thêm văn bản từ chuỗi html được chỉ định vào bộ sưu tập. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Chuyển đổi các đoạn văn đã chỉ định sang HTML và trả về dưới dạng đối tượng String. |

### getCount() {#getCount--}
```
public final int getCount()
```

Lấy số phần tử thực sự chứa trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Lấy giá trị cho biết liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có phải chỉ đọc hay không. Chỉ đọc boolean.

**Trả về:**
boolean - true nếu [IGenericCollection](../../com.aspose.slides/igenericcollection) là chỉ đọc; ngược lại, false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Thêm một Paragraph vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph sẽ được thêm vào cuối bộ sưu tập. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Thêm nội dung của ParagraphCollection vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection sẽ được thêm vào cuối bộ sưu tập. |

**Trả về:**
int - Chỉ mục mà Paragraph đã được thêm vào hoặc -1 nếu không có gì để thêm.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Xác định chỉ mục của một mục cụ thể trong List.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Đối tượng cần tìm trong List. |

**Trả về:**
int - Chỉ mục của mục nếu tìm thấy trong danh sách; nếu không, -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Chèn một Paragraph vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 mà Paragraph sẽ được chèn vào. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph sẽ được chèn. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Chèn nội dung của ParagraphCollection vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 mà các đoạn văn sẽ được chèn vào. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Các đoạn văn sẽ được chèn. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Xác định liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Đối tượng cần tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu tìm thấy mục trong [IGenericCollection](../../com.aspose.slides/igenericcollection); ngược lại, false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một Mảng, bắt đầu tại một chỉ mục Mảng cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Mảng một chiều là đích đến của các phần tử được sao chép từ [IGenericCollection](../../com.aspose.slides/igenericcollection). Mảng phải có chỉ mục bắt đầu từ 0. |
| arrayIndex | int | Chỉ mục bắt đầu từ 0 trong mảng mà việc sao chép bắt đầu. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã chỉ định của bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của phần tử cần xóa. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Đối tượng cần xóa khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu mục đã được xóa thành công khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection); ngược lại, false. Phương thức này cũng trả về false nếu không tìm thấy mục trong [IGenericCollection](../../com.aspose.slides/igenericcollection) gốc.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Trả về một enumerator cho phép duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator cho toàn bộ bộ sưu tập.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của một bộ sưu tập các đoạn văn. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của một bộ sưu tập các đoạn văn. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Thêm văn bản từ chuỗi html được chỉ định vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Thêm văn bản từ chuỗi html được chỉ định vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| text | java.lang.String | Văn bản HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Đối tượng callback Resolver, giải quyết các URI và lấy các đối tượng được tham chiếu. |
| uri | java.lang.String | URI để thêm tài liệu HTML. Được sử dụng để giải quyết các liên kết tương đối. |

--------------------
Chỉ định resolver có thể tiềm ẩn lỗ hổng bảo mật. Sử dụng cẩn thận. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Chuyển đổi các đoạn văn đã chỉ định sang HTML và trả về dưới dạng đối tượng String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| firstParagraphIndex | int | Chỉ mục đoạn văn đầu tiên int |
| paragraphsCount | int | Số lượng đoạn văn int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Các tùy chọn chuyển đổi [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Trả về:**
java.lang.String - HTML đã tạo.