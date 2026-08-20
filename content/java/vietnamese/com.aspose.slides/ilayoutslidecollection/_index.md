---
title: ILayoutSlideCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho lớp cơ sở của bộ sưu tập các slide bố cục.
type: docs
url: /vi/com.aspose.slides/ilayoutslidecollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Đại diện cho một lớp cơ sở cho bộ sưu tập các slide bố cục.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về slide bố cục theo chỉ mục. |
| [getByType(byte type)](#getByType-byte-) | Trả về slide bố cục đầu tiên có kiểu đã chỉ định. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Xóa một bố cục khỏi bộ sưu tập. |
| [removeUnused()](#removeUnused--) | Xóa các slide bố cục không sử dụng (các slide bố cục có HasDependingSlides là false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Trả về slide bố cục theo chỉ mục. Chỉ-đọc [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

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


Trả về slide bố cục đầu tiên có kiểu đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | byte | Kiểu của slide bố cục cần tìm. |

**Giá trị trả về:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) với kiểu đã chỉ định hoặc null nếu không tìm thấy bố cục.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Xóa một bố cục khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bố cục slide cần xóa khỏi bộ sưu tập.

--------------------

1) Để tránh việc ném PptxEditException, hãy kiểm tra thuộc tính HasDependingSlides của layout trước. 2) Bạn cũng có thể sử dụng phương thức [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) để đơn giản hoá mã. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Xóa các slide bố cục không sử dụng (các slide bố cục có HasDependingSlides là false).