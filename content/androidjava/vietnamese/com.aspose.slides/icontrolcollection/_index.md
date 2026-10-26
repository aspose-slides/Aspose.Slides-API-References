---
title: IControlCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Một bộ sưu tập các điều khiển ActiveX.
type: docs
url: /vi/com.aspose.slides/icontrolcollection/
---
**Tất cả các giao diện được thực thi:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Một bộ sưu tập các điều khiển ActiveX.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Xóa một điều khiển ActiveX khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa một điều khiển ActiveX được lưu tại vị trí xác định khỏi bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các điều khiển khỏi bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về một điều khiển tại vị trí được chỉ định. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Tạo và thêm một điều khiển mới vào bộ sưu tập. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Xóa một điều khiển ActiveX khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Một điều khiển để xóa. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa một điều khiển ActiveX được lưu tại vị trí xác định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của điều khiển cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các điều khiển khỏi bộ sưu tập.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Trả về một điều khiển tại vị trí được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một điều khiển. |

**Trả về:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Tạo và thêm một điều khiển mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| controlType | int | Kiểu của một điều khiển để thêm. |
| x | float | Tọa độ X cho phía trái của khung hình dạng. |
| y | float | Tọa độ Y cho phía trên của khung hình dạng. |
| width | float | Chiều rộng của khung hình dạng. |
| height | float | Chiều cao của khung hình dạng. |

**Trả về:**
[IControl](../../com.aspose.slides/icontrol) - Điều khiển đã tạo [IControl](../../com.aspose.slides/icontrol).