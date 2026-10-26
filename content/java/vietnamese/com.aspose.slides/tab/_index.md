---
title: Tab
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một tab cho văn bản.
type: docs
url: /vi/com.aspose.slides/tab/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Biểu diễn một tab cho văn bản.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Tạo Tab mới |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Trả về hoặc thiết lập vị trí của tab. |
| [setPosition(double value)](#setPosition-double-) | Trả về hoặc thiết lập vị trí của tab. |
| [getAlignment()](#getAlignment--) | Trả về hoặc thiết lập kiểu căn chỉnh của tab. |
| [setAlignment(int value)](#setAlignment-int-) | Trả về hoặc thiết lập kiểu căn chỉnh của tab. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | So sánh thể hiện hiện tại với một đối tượng khác cùng kiểu. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


Tạo Tab mới

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | double | Vị trí của Tab. |
| align | int | Căn chỉnh. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Phiên bản. Long chỉ đọc.

**Kết quả:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


Trả về hoặc thiết lập vị trí của tab. Gán thuộc tính này có thể thay đổi chỉ mục của tab trong bộ sưu tập và làm mất hiệu lực của Enumerator. double đọc/ghi.

**Kết quả:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


Trả về hoặc thiết lập vị trí của tab. Gán thuộc tính này có thể thay đổi chỉ mục của tab trong bộ sưu tập và làm mất hiệu lực của Enumerator. double đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Trả về hoặc thiết lập kiểu căn chỉnh của tab. đọc/ghi [TabAlignment](../../com.aspose.slides/tabalignment).

**Kết quả:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Trả về hoặc thiết lập kiểu căn chỉnh của tab. đọc/ghi [TabAlignment](../../com.aspose.slides/tabalignment).

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

**Kết quả:**
int - Một số nguyên 32-bit cho biết thứ tự tương đối của các đối tượng so sánh. Giá trị trả về có ý nghĩa:

 * < 0 - Thể hiện này nhỏ hơn obj.
 * = 0 - Thể hiện này bằng obj.
 * > 0 - Thể hiện này lớn hơn obj.