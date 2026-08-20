---
title: ImageTransformOCollectionEffectiveData
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đối tượng bất biến đại diện cho một bộ sưu tập chỉ đọc của các hiệu ứng biến đổi ảnh hiệu quả.
type: docs
url: /vi/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

Đối tượng bất biến đại diện cho một collection chỉ đọc của các hiệu ứng biến đổi ảnh hiệu quả.

--------------------

Tên IImageTransformOperationCollectionEffectiveData bị rút gọn thành IImageTransformOCollectionEffectiveData vì độ dài tên COM không được vượt quá 39 ký tự.
## Phương thức khởi tạo

| Constructor | Description |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng hiệu ứng ảnh trong một collection. |
| [get_Item(int index)](#get-Item-int-) | Trả về phần tử theo chỉ số. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem đối tượng được chỉ định có bằng với đối tượng hiện tại hay không. |
| [hashCode()](#hashCode--) | Hoạt động như một hàm băm cho một kiểu cụ thể, thích hợp cho việc sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua collection. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ collection vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào collection có được đồng bộ (an toàn với đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```

### size() {#size--}
```
public final int size()
```

Trả về số lượng hiệu ứng ảnh trong một collection. Kiểu int chỉ đọc.

**Giá trị trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```

Trả về phần tử theo chỉ số.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của phần tử. |

**Giá trị trả về:**
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

**Giá trị trả về:**
boolean - true nếu đối tượng được chỉ định bằng với đối tượng hiện tại; ngược lại, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hoạt động như một hàm băm cho một kiểu cụ thể, thích hợp cho việc sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm.

**Giá trị trả về:**
int - Mã băm cho đối tượng hiện tại.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```

Trả về một enumerator cho phép duyệt qua collection.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Một IGenericEnumerator có thể được sử dụng để duyệt qua collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```

Trả về một java iterator cho toàn bộ collection.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - Một java.util.Iterator cho toàn bộ collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ collection vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng để điền. |
| index | int | Vị trí bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào collection có được đồng bộ (an toàn với đa luồng) hay không. Kiểu boolean chỉ đọc.

**Giá trị trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Đối tượng Object chỉ đọc.

**Giá trị trả về:**
java.lang.Object