---
title: BiLevel
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn hiệu ứng đen/trắng Bi-Level.
type: docs
url: /vi/com.aspose.slides/bilevel/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả Các Giao Diện Được Thực Thi:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Biểu diễn một hiệu ứng Bi-Level (đen/trắng). Các màu đầu vào có độ sáng thấp hơn giá trị ngưỡng đã chỉ định sẽ được chuyển sang màu đen. Các màu đầu vào có độ sáng lớn hơn hoặc bằng giá trị đã chỉ định sẽ được đặt thành màu trắng. Các giá trị hiệu ứng alpha không bị ảnh hưởng bởi hiệu ứng này.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Bi-Level hiệu quả với việc kế thừa được áp dụng. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [BiLevel](../../com.aspose.slides/bilevel) đã chỉ định có bằng với [BiLevel](../../com.aspose.slides/bilevel) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò là hàm băm cho một kiểu cụ thể. |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Bi-Level hiệu quả với việc kế thừa được áp dụng.

**Trả về:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Một [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem [BiLevel](../../com.aspose.slides/bilevel) đã chỉ định có bằng với [BiLevel](../../com.aspose.slides/bilevel) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [BiLevel](../../com.aspose.slides/bilevel) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò là hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.