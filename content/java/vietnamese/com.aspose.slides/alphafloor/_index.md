---
title: AlphaFloor
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một hiệu ứng Alpha Floor.
type: docs
url: /vi/com.aspose.slides/alphafloor/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Biểu diễn một hiệu ứng Alpha Floor. Các giá trị Alpha (độ trong suốt) nhỏ hơn 100% sẽ được thay đổi thành zero. Nói cách khác, bất kỳ phần nào có độ trong suốt một phần sẽ trở nên hoàn toàn trong suốt.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Floor effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaFloor](../../com.aspose.slides/alphafloor) is equal to the current [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

Lấy dữ liệu hiệu ứng Alpha Floor đã áp dụng kế thừa.

**Trả về:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Một [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem [AlphaFloor](../../com.aspose.slides/alphafloor) được chỉ định có bằng với [AlphaFloor](../../com.aspose.slides/alphafloor) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng [AlphaFloor](../../com.aspose.slides/alphafloor) để so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò là hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.