---
title: SectionCollection
second_title: Aspose.Slides cho Android qua Java API Reference
description: Đại diện cho một collection các section.
type: docs
url: /vi/com.aspose.slides/sectioncollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các Interface được triển khai:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Đại diện cho một collection các phần.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Thêm phần slides bắt đầu từ slide cụ thể. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Thêm phần trống vào cuối collection. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Thêm phần trống vào vị trí được chỉ định trong collection. |
| [size()](#size--) | Lấy số lượng phần tử thực tế có trong collection. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Trả về chỉ mục của phần được chỉ định trong collection. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Xóa phần và các slide chứa trong phần. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Xóa phần. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Di chuyển phần và các slide của nó từ collection tới vị trí được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần khỏi collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép toàn bộ collection tới mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết liệu việc truy cập vào collection có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua collection. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [ISection](../../com.aspose.slides/isection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Thêm phần slides bắt đầu từ slide cụ thể.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Tên của phần |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Slide đầu tiên của phần |

**Trả về:**
[ISection](../../com.aspose.slides/isection) - Đã thêm phần.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Thêm phần trống vào cuối collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Tên của phần |

**Trả về:**
[ISection](../../com.aspose.slides/isection) - Đã thêm phần.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Thêm phần trống vào vị trí được chỉ định trong collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Tên của phần |
| index | int | Chỉ mục của phần mới. |

**Trả về:**
[ISection](../../com.aspose.slides/isection) - Đã thêm phần.
### size() {#size--}
```
public final int size()
```

Lấy số lượng phần tử thực tế có trong collection. Chỉ đọc int.

**Trả về:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Trả về chỉ mục của phần được chỉ định trong collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần tìm. |

**Trả về:**
int - Chỉ mục của phần hoặc -1 nếu phần không thuộc collection này.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Xóa phần và các slide chứa trong phần.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần xóa khỏi collection. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Xóa phần. Các slide trong phần sẽ được hợp nhất vào phần trước.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần xóa khỏi collection. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Di chuyển phần và các slide của nó từ collection tới vị trí được chỉ định.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần di chuyển. |
| index | int | Chỉ mục đích. |
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần khỏi collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép toàn bộ collection tới mảng được chỉ định.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích |
| index | int | Chỉ mục trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết liệu việc truy cập vào collection có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

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

Trả về một enumerator duyệt qua collection.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Một IGenericEnumerator có thể được dùng để duyệt qua collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Trả về một java iterator cho toàn bộ collection.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Một java.util.Iterator cho toàn bộ collection.