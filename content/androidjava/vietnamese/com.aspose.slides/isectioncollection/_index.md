---
title: ISectionCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu thị một bộ sưu tập các phần.
type: docs
url: /vi/com.aspose.slides/isectioncollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Biểu thị một bộ sưu tập các phần.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Thêm phần mới bắt đầu từ slide cụ thể. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Thêm phần trống vào vị trí được chỉ định trong bộ sưu tập. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Xóa phần và các slide chứa trong phần. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Xóa phần. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Di chuyển phần và các slide của nó từ bộ sưu tập đến vị trí được chỉ định. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Thêm phần trống vào cuối bộ sưu tập. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Trả về chỉ mục của phần được chỉ định trong bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các phần khỏi bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [ISection](../../com.aspose.slides/isection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Thêm phần mới bắt đầu từ slide cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của phần |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Slide đầu tiên của phần |

**Trả về:**
[ISection](../../com.aspose.slides/isection) - Phần đã thêm.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Thêm phần trống vào vị trí được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của phần |
| index | int | Chỉ mục của phần mới. |

**Trả về:**
[ISection](../../com.aspose.slides/isection) - Phần đã thêm.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Xóa phần và các slide chứa trong phần.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần xóa khỏi bộ sưu tập. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Xóa phần. Các slide chứa trong phần sẽ được hợp nhất vào phần trước.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần xóa khỏi bộ sưu tập. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Di chuyển phần và các slide của nó từ bộ sưu tập đến vị trí được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần di chuyển. |
| index | int | Chỉ mục mục tiêu. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Thêm phần trống vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của phần |

**Trả về:**
[ISection](../../com.aspose.slides/isection) - Phần đã thêm.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Trả về chỉ mục của phần được chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cần tìm. |

**Trả về:**
int - Chỉ mục của phần hoặc -1 nếu phần không thuộc bộ sưu tập này.
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần khỏi bộ sưu tập.