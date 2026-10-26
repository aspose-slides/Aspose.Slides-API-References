---
title: GradientStopCollectionEffectiveData
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Biểu thị một bộ sưu tập các đối tượng GradientStopData.
type: docs
url: /vi/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**Kế thừa:**  
java.lang.Object

**Tất cả các giao diện được triển khai:**  
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)  
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

Biểu thị một collection của các đối tượng GradientStopData.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng gradient stop trong collection. |
| [get_Item(int index)](#get-Item-int-) | Trả về gradient stop theo chỉ mục. |
| [iterator()](#iterator--) | Trả về một enumerator mà lặp qua collection. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ collection sang mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết liệu việc truy cập vào collection có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |

### size() {#size--}
```
public final int size()
```

Trả về số lượng gradient stop trong collection. Chỉ đọc int.

**Trả về:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

Trả về gradient stop theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**  
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

Trả về một enumerator mà lặp qua collection.

**Trả về:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

Trả về một java iterator cho toàn bộ collection.

**Trả về:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ collection sang mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về một giá trị cho biết liệu việc truy cập vào collection có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**  
java.lang.Object