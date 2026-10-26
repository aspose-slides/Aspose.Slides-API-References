---
title: AlphaInverse
second_title: Tham khảo API Java của Aspose.Slides cho Android
description: Biểu diễn một hiệu ứng Alpha Inverse.
type: docs
url: /vi/com.aspose.slides/alphainverse/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Biểu diễn một hiệu ứng Alpha Inverse. Các giá trị Alpha (opacity) được đảo ngược bằng cách trừ khỏi 100%.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Alpha Inverse đã áp dụng kế thừa. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [AlphaInverse](../../com.aspose.slides/alphainverse) được chỉ định có bằng với [AlphaInverse](../../com.aspose.slides/alphainverse) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu cụ thể. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Alpha Inverse đã áp dụng kế thừa.

**Trả về:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - Một [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Long chỉ đọc.

**Trả về:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem [AlphaInverse](../../com.aspose.slides/alphainverse) được chỉ định có bằng với [AlphaInverse](../../com.aspose.slides/alphainverse) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaInverse](../../com.aspose.slides/alphainverse) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò như một hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.