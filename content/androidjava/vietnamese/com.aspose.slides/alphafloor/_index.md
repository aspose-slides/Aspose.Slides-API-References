---
title: AlphaFloor
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một hiệu ứng Alpha Floor.
type: docs
url: /vi/com.aspose.slides/alphafloor/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Đại diện cho hiệu ứng Alpha Floor. Giá trị Alpha (độ trong suốt) nhỏ hơn 100% sẽ được thay đổi thành zero. Nói cách khác, bất kỳ phần nào có độ trong suốt một phần sẽ trở thành hoàn toàn trong suốt.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEffective()](#getEffective--) | Lấy dữ liệu hiệu ứng Alpha Floor hiệu quả với kế thừa đã được áp dụng. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem [AlphaFloor](../../com.aspose.slides/alphafloor) được chỉ định có bằng với [AlphaFloor](../../com.aspose.slides/alphafloor) hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu cụ thể. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Lấy dữ liệu hiệu ứng Alpha Floor hiệu quả với kế thừa đã được áp dụng.

**Trả về:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - một [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Xác định xem [AlphaFloor](../../com.aspose.slides/alphafloor) được chỉ định có bằng với [AlphaFloor](../../com.aspose.slides/alphafloor) hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaFloor](../../com.aspose.slides/alphafloor) sẽ so sánh. |

**Trả về:**
boolean - true nếu các đối tượng bằng nhau; ngược lại, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Đóng vai trò như một hàm băm cho một kiểu cụ thể.

**Trả về:**
int - Một mã băm cho đối tượng hiện tại.