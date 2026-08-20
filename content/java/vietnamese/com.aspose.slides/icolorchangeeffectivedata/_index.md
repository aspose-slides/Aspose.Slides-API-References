---
title: IColorChangeEffectiveData
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đối tượng bất biến đại diện cho hiệu ứng Thay đổi Màu.
type: docs
url: /vi/com.aspose.slides/icolorchangeeffectivedata/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Đối tượng bất biến đại diện cho hiệu ứng Thay đổi Màu. Các thể hiện của FromColor được thay thế bằng các thể hiện của ToColor.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFromColor()](#getFromColor--) | Màu sẽ được thay thế. |
| [getToColor()](#getToColor--) | Màu sẽ thay thế. |
| [getUseAlpha()](#getUseAlpha--) | Trả về giá trị boolean xác định xem thành phần alpha có nên được sử dụng hay không. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


Màu sẽ được thay thế. Chỉ đọc java.awt.Color.

**Trả về:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


Màu sẽ thay thế. Chỉ đọc java.awt.Color.

**Trả về:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


Trả về giá trị boolean xác định xem thành phần alpha có nên được sử dụng hay không. Chỉ đọc boolean.

**Trả về:**
boolean