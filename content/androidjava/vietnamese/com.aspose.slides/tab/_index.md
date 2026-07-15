---
title: Tab
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một tab trong văn bản.
type: docs
url: /vi/com.aspose.slides/tab/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả giao diện được triển khai:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Đại diện cho một tab trong văn bản.
## Các hàm khởi tạo

| Hằng khởi tạo | Mô tả |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Tạo Tab mới |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Trả về hoặc đặt vị trí của một tab. |
| [setPosition(double value)](#setPosition-double-) | Trả về hoặc đặt vị trí của một tab. |
| [getAlignment()](#getAlignment--) | Trả về hoặc đặt kiểu căn chỉnh của một tab. |
| [setAlignment(int value)](#setAlignment-int-) | Trả về hoặc đặt kiểu căn chỉnh của một tab. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | So sánh thể hiện hiện tại với một đối tượng khác cùng kiểu. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Tạo Tab mới

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | double | Vị trí của tab. |
| align | int | Căn chỉnh. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc kiểu long.

**Trả về:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Trả về hoặc đặt vị trí của một tab. Gán giá trị cho thuộc tính này có thể thay đổi chỉ mục của tab trong bộ sưu tập và làm cho Enumerator trở nên không hợp lệ. Đọc/ghi kiểu double.

**Trả về:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Trả về hoặc đặt vị trí của một tab. Gán giá trị cho thuộc tính này có thể thay đổi chỉ mục của tab trong bộ sưu tập và làm cho Enumerator trở nên không hợp lệ. Đọc/ghi kiểu double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Trả về hoặc đặt kiểu căn chỉnh của một tab. Đọc/ghi [TabAlignment](../../com.aspose.slides/tabalignment).

**Trả về:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Trả về hoặc đặt kiểu căn chỉnh của một tab. Đọc/ghi [TabAlignment](../../com.aspose.slides/tabalignment).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

So sánh thể hiện hiện tại với một đối tượng khác cùng kiểu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Một đối tượng để so sánh với thể hiện này. |

**Trả về:**
int - Một số nguyên 32-bit cho biết thứ tự tương đối của các đối tượng được so sánh. Giá trị trả về có các nghĩa sau:

 * < 0 - Thể hiện này nhỏ hơn obj.
 * = 0 - Thể hiện này bằng obj.
 * > 0 - Thể hiện này lớn hơn obj.