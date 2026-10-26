---
title: ISmartArt
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một sơ đồ SmartArt.
type: docs
url: /vi/com.aspose.slides/ismartart/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Biểu diễn một sơ đồ SmartArt.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Trả về tập hợp các nút trong đối tượng SmartArt. |
| [getNodes()](#getNodes--) | Trả về tập hợp các nút gốc trong đối tượng SmartArt. |
| [getLayout()](#getLayout--) | Lấy hoặc đặt bố cục của đối tượng SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Lấy hoặc đặt bố cục của đối tượng SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Lấy hoặc đặt kiểu nhanh của đối tượng SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Lấy hoặc đặt kiểu nhanh của đối tượng SmartArt. |
| [getColorStyle()](#getColorStyle--) | Lấy hoặc đặt kiểu màu của đối tượng SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Lấy hoặc đặt kiểu màu của đối tượng SmartArt. |
| [isReversed()](#isReversed--) | Lấy hoặc đặt trạng thái của sơ đồ SmartArt liên quan đến (trái sang phải) LTR hoặc (phải sang trái) RTL, nếu sơ đồ hỗ trợ đảo ngược. |
| [setReversed(boolean value)](#setReversed-boolean-) | Lưa hoặc đặt trạng thái của sơ đồ SmartArt liên quan đến (trái sang phải) LTR hoặc (phải sang trái) RTL, nếu sơ đồ hỗ trợ đảo ngược. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Trả về tập hợp các nút trong đối tượng SmartArt. Chỉ đọc [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Trả về:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Trả về tập hợp các nút gốc trong đối tượng SmartArt. Chỉ đọc [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Trả về:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Lấy hoặc đặt bố cục của đối tượng SmartArt. Đọc/ghi [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Trả về:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Lấy hoặc đặt bố cục của đối tượng SmartArt. Đọc/ghi [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Lấy hoặc đặt kiểu nhanh của đối tượng SmartArt. Đọc/ghi [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Trả về:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickShape(int value)
```


Lấy hoặc đặt kiểu nhanh của đối tượng SmartArt. Đọc/ghi [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Lấy hoặc đặt kiểu màu của đối tượng SmartArt. Đọc/ghi [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Trả về:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Lấy hoặc đặt kiểu màu của đối tượng SmartArt. Đọc/ghi [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Lấy hoặc đặt trạng thái của sơ đồ SmartArt liên quan đến (trái sang phải) LTR hoặc (phải sang trái) RTL, nếu sơ đồ hỗ trợ đảo ngược. Đọc/ghi boolean.

**Trả về:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Lấy hoặc đặt trạng thái của sơ đồ SmartArt liên quan đến (trái sang phải) LTR hoặc (phải sang trái) RTL, nếu sơ đồ hỗ trợ đảo ngược. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |