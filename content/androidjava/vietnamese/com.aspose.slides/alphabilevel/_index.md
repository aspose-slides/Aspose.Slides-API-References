---
title: AlphaBiLevel
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một hiệu ứng Alpha Bi-Level.
type: docs
url: /vi/com.aspose.slides/alphabilevel/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Biểu diễn một hiệu ứng Alpha Bi-Level. Các giá trị Alpha (Độ mờ) nhỏ hơn ngưỡng sẽ được đổi thành 0 (hoàn toàn trong suốt) và các giá trị alpha lớn hơn hoặc bằng ngưỡng sẽ được đổi thành 100% (hoàn toàn không trong suốt).
## Phương thức

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Trả về ngưỡng hiệu ứng. |
| [setThreshold(float value)](#setThreshold-float-) | Trả về ngưỡng hiệu ứng. |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Alpha Bi-Level hiệu lực với kế thừa đã được áp dụng. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [AlphaBiLevel](../../com.aspose.slides/alphabilevel) đã chỉ định có bằng với [AlphaBiLevel](../../com.aspose.slides/alphabilevel) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò là hàm băm cho một kiểu cụ thể. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Trả về ngưỡng hiệu ứng. Đọc/ghi float.

**Trả về:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Trả về ngưỡng hiệu ứng. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


Lấy dữ liệu hiệu ứng Alpha Bi-Level hiệu lực với kế thừa đã được áp dụng.

**Trả về:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Xác định xem [AlphaBiLevel](../../com.aspose.slides/alphabilevel) đã chỉ định có bằng với [AlphaBiLevel](../../com.aspose.slides/alphabilevel) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Đóng vai trò là hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.