---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đối tượng bất biến đại diện cho một bộ sưu tập chỉ đọc của các hiệu ứng biến đổi hình ảnh hiệu quả.
type: docs
url: /vi/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

Đối tượng bất biến đại diện cho một bộ sưu tập chỉ đọc của các hiệu ứng biến đổi hình ảnh hiệu quả.

--------------------

Tên IImageTransformOperationCollectionEffectiveData được rút gọn thành IImageTransformOCollectionEffectiveData vì độ dài tên COM không được vượt quá 39.
## Các hàm tạo

| Constructor | Description |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## Phương thức

| Method | Description |
| --- | --- |
| [size()](#size--) | Trả về số lượng hiệu ứng hình ảnh trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về phần tử theo chỉ mục. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem đối tượng được chỉ định có bằng với đối tượng hiện tại hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò như hàm băm cho một kiểu cụ thể, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ hoá. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


Trả về số lượng hiệu ứng hình ảnh trong bộ sưu tập. int chỉ đọc.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


Trả về phần tử theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử. |

**Trả về:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - Đối tượng [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Xác định xem đối tượng được chỉ định có bằng với đối tượng hiện tại hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng để so sánh với đối tượng hiện tại. |

**Trả về:**
boolean - true nếu đối tượng được chỉ định bằng với đối tượng hiện tại; ngược lại, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Đóng vai trò như hàm băm cho một kiểu cụ thể, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm.

**Trả về:**
int - Mã băm cho đối tượng hiện tại.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


Trả về một iterator java cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng để điền. |
| index | int | Vị trí bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị cho biết việc truy cập vào bộ sưu tập có được đồng bộ (an toàn với luồng) hay không. boolean chỉ đọc.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một gốc đồng bộ hoá. Object chỉ đọc.

**Trả về:**
java.lang.Object