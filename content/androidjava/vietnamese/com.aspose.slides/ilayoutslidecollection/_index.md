---
title: ILayoutSlideCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một lớp cơ sở cho tập hợp các slide bố cục.
type: docs
url: /vi/com.aspose.slides/ilayoutslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Đại diện cho một lớp cơ sở cho tập hợp các layout slide.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về layout slide theo chỉ số. |
| [getByType(byte type)](#getByType-byte-) | Trả về layout slide đầu tiên của loại được chỉ định. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Xóa một layout khỏi tập hợp. |
| [removeUnused()](#removeUnused--) | Xóa các layout slide không sử dụng (các layout slide mà HasDependingSlides là false). |

### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Trả về layout slide theo chỉ số. Chỉ đọc [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Trả về layout slide đầu tiên của loại được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | byte | Một loại layout slide cần tìm. |

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) với loại được chỉ định hoặc null nếu không tìm thấy layout nào.

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Xóa một layout khỏi tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout slide cần xóa khỏi tập hợp.

---

1) Để tránh ném PptxEditException, hãy kiểm tra thuộc tính HasDependingSlides của layout trước. 2) Bạn cũng có thể sử dụng phương thức [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) để đơn giản hoá mã. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Xóa các layout slide không sử dụng (các layout slide mà HasDependingSlides là false).