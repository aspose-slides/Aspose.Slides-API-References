---
title: AlphaInverse
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho hiệu ứng Đảo ngược Alpha.
type: docs
url: /vi/com.aspose.slides/alphainverse/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Đại diện cho hiệu ứng Đảo ngược Alpha. Giá trị Alpha (độ mờ) được đảo ngược bằng cách trừ khỏi 100%.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Đảo ngược Alpha hiệu lực với việc kế thừa đã được áp dụng. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [AlphaInverse](../../com.aspose.slides/alphainverse) được chỉ định có bằng với [AlphaInverse](../../com.aspose.slides/alphainverse) hiện tại không. |
| [hashCode()](#hashCode--) | Hoạt động như một hàm băm cho một loại cụ thể. |

### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Đảo ngược Alpha hiệu lực với việc kế thừa đã được áp dụng.

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

Xác định xem [AlphaInverse](../../com.aspose.slides/alphainverse) được chỉ định có bằng với [AlphaInverse](../../com.aspose.slides/alphainverse) hiện tại không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng [AlphaInverse](../../com.aspose.slides/alphainverse) cần so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; nếu không, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Hoạt động như một hàm băm cho một loại cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.