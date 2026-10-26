---
title: SectionCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bộ sưu tập các phần.
type: docs
url: /vi/com.aspose.slides/sectioncollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Biểu diễn một bộ sưu tập các phần.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại vị trí được chỉ định. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Thêm phần của các slide bắt đầu từ slide cụ thể. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Thêm phần trống vào cuối bộ sưu tập. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Thêm phần trống vào vị trí được chỉ định trong bộ sưu tập. |
| [size()](#size--) | Lấy số lượng phần tử thực tế có trong bộ sưu tập. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Trả về chỉ mục của phần được chỉ định trong bộ sưu tập. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Xóa phần và các slide chứa trong phần. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Xóa phần. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Di chuyển phần và các slide của nó từ bộ sưu tập đến vị trí được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần khỏi bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép toàn bộ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```


Lấy phần tử tại vị trí được chỉ định. Chỉ đọc [ISection](../../com.aspose.slides/isection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```


Thêm phần của các slide bắt đầu từ slide cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của phần |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Slide đầu tiên của phần |

**Trả về:**
[ISection](../../com.aspose.slides/isection) - Phần đã thêm.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```


Thêm phần trống vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của phần |

**Trả về:**
[ISection](../../com.aspose.slides/isection) - Phần đã thêm.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```


Thêm phần trống vào vị trí được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của phần |
| index | int | Chỉ mục của phần mới. |

**Trả về:**
[ISection](../../com.aspose.slides/isection) - Phần đã thêm.
### size() {#size--}
```
public final int size()
```


Lấy số lượng phần tử thực tế có trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```


Trả về chỉ mục của phần được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần tìm. |

**Trả về:**
int - Chỉ mục của một phần hoặc -1 nếu phần không thuộc bộ sưu tập này.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```


Xóa phần và các slide chứa trong phần.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần xóa khỏi bộ sưu tập. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```


Xóa phần. Các slide trong phần sẽ được hợp nhất vào phần trước.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần xóa khỏi bộ sưu tập. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```


Di chuyển phần và các slide của nó từ bộ sưu tập đến vị trí được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần di chuyển. |
| index | int | Chỉ mục mục tiêu. |

### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các phần khỏi bộ sưu tập.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép toàn bộ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng mục tiêu |
| index | int | Chỉ mục trong mảng mục tiêu. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với đa luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về gốc đồng bộ. Chỉ đọc Object.

**Trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```


Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```


Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Một java.util.Iterator cho toàn bộ bộ sưu tập.