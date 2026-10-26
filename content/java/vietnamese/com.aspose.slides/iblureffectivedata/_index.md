---
title: IBlurEffectiveData
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đối tượng bất biến đại diện cho hiệu ứng Blur được áp dụng cho toàn bộ hình dạng, bao gồm cả phần tô màu.
type: docs
url: /vi/com.aspose.slides/iblureffectivedata/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Đối tượng bất biến đại diện cho hiệu ứng Blur được áp dụng cho toàn bộ hình dạng, bao gồm cả phần tô màu. Tất cả các kênh màu, bao gồm cả alpha, đều bị ảnh hưởng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRadius()](#getRadius--) | Trả về hoặc thiết lập bán kính làm mờ. |
| [getGrow()](#getGrow--) | Xác định xem giới hạn của đối tượng có nên mở rộng do hiệu ứng làm mờ hay không. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Trả về hoặc thiết lập bán kính làm mờ. Chỉ-đọc double.

**Trả về:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Xác định xem giới hạn của đối tượng có nên mở rộng do hiệu ứng làm mờ hay không. True cho biết giới hạn được mở rộng trong khi false cho biết không được mở rộng. Chỉ-đọc boolean.

**Trả về:**
boolean