---
title: ISmartArt
second_title: Tham khảo API Java của Aspose.Slides cho Android
description: Biểu diễn một sơ đồ SmartArt.
type: docs
url: /vi/com.aspose.slides/ismartart/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Biểu diễn một sơ đồ SmartArt.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Trả về tập hợp các nút tất cả trong đối tượng SmartArt. |
| [getNodes()](#getNodes--) | Trả về tập hợp các nút gốc trong đối tượng SmartArt. |
| [getLayout()](#getLayout--) | Trả về hoặc đặt bố cục của đối tượng SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Trả về hoặc đặt bố cục của đối tượng SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Trả về hoặc đặt kiểu nhanh của đối tượng SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Trả về hoặc đặt kiểu nhanh của đối tượng SmartArt. |
| [getColorStyle()](#getColorStyle--) | Trả về hoặc đặt kiểu màu của đối tượng SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Trả về hoặc đặt kiểu màu của đối tượng SmartArt. |
| [isReversed()](#isReversed--) | Trả về hoặc đặt trạng thái của sơ đồ SmartArt liên quan đến (trái sang phải) LTR hoặc (phải sang trái) RTL, nếu sơ đồ hỗ trợ đảo ngược. |
| [setReversed(boolean value)](#setReversed-boolean-) | Trả về hoặc đặt trạng thái của sơ đồ SmartArt liên quan đến (trái sang phải) LTR hoặc (phải sang trái) RTL, nếu sơ đồ hỗ trợ đảo ngược. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Trả về tập hợp các nút tất cả trong đối tượng SmartArt. Chỉ đọc [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

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


Trả về hoặc đặt bố cục của đối tượng SmartArt. Đọc/ghi [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Trả về:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Trả về hoặc đặt bố cục của đối tượng SmartArt. Đọc/ghi [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Trả về hoặc đặt kiểu nhanh của đối tượng SmartArt. Đọc/ghi [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Trả về:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Trả về hoặc đặt kiểu nhanh của đối tượng SmartArt. Đọc/ghi [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Trả về hoặc đặt kiểu màu của đối tượng SmartArt. Đọc/ghi [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Trả về:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Trả về hoặc đặt kiểu màu của đối tượng SmartArt. Đọc/ghi [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Trả về hoặc đặt trạng thái của sơ đồ SmartArt liên quan đến (trái sang phải) LTR hoặc (phải sang trái) RTL, nếu sơ đồ hỗ trợ đảo ngược. Đọc/ghi boolean.

**Trả về:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Trả về hoặc đặt trạng thái của sơ đồ SmartArt liên quan đến (trái sang phải) LTR hoặc (phải sang trái) RTL, nếu sơ đồ hỗ trợ đảo ngược. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |