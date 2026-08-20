---
title: IControlCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Một tập hợp các điều khiển ActiveX.
type: docs
url: /vi/com.aspose.slides/icontrolcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Một tập hợp các điều khiển ActiveX.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Loại bỏ một điều khiển ActiveX khỏi tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Loại bỏ một điều khiển ActiveX được lưu tại vị trí xác định khỏi tập hợp. |
| [clear()](#clear--) | Loại bỏ tất cả các điều khiển khỏi tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Trả về một điều khiển tại vị trí xác định. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Tạo và thêm một điều khiển mới vào tập hợp. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```


Loại bỏ một điều khiển ActiveX khỏi tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Một điều khiển để loại bỏ. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Loại bỏ một điều khiển ActiveX được lưu tại vị trí xác định khỏi tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của điều khiển cần loại bỏ. |

### clear() {#clear--}
```
public abstract void clear()
```


Loại bỏ tất cả các điều khiển khỏi tập hợp.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```


Trả về một điều khiển tại vị trí xác định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một điều khiển. |

**Giá trị trả về:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```


Tạo và thêm một điều khiển mới vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| controlType | int | Kiểu của điều khiển cần thêm. |
| x | float | Tọa độ X của phía trái khung hình dạng. |
| y | float | Tọa độ Y của phía trên khung hình dạng. |
| width | float | Chiều rộng của khung hình dạng. |
| height | float | Chiều cao của khung hình dạng. |

**Giá trị trả về:**
[IControl](../../com.aspose.slides/icontrol) - Điều khiển đã tạo [IControl](../../com.aspose.slides/icontrol).