---
title: EffectStyleCollection
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho một tập hợp các kiểu hiệu ứng.
type: docs
url: /vi/com.aspose.slides/effectstylecollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

Biểu diễn một tập hợp các kiểu hiệu ứng.
## Phương thức

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về một phần tử tại vị trí được chỉ định. |
| [iterator()](#iterator--) | Trả về một trình lặp duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [size()](#size--) | Trả về số lượng phần tử trong tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết liệu việc truy cập vào tập hợp có được đồng bộ (an toàn với luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ. |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

Trả về một phần tử tại vị trí được chỉ định. Chỉ đọc [EffectStyle](../../com.aspose.slides/effectstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Vị trí của phần tử. |

**Trả về:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - Phần tử tại vị trí được chỉ định.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

Trả về một trình lặp duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Một IGenericEnumerator có thể được sử dụng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - Một java.util.Iterator cho toàn bộ tập hợp.
### size() {#size--}
```
public final int size()
```

Trả về số lượng phần tử trong tập hợp. Chỉ đọc int, Chỉ đọc int.

**Trả về:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ tập hợp vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết liệu việc truy cập vào tập hợp có được đồng bộ (an toàn với luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một gốc đồng bộ. Chỉ đọc Object.

**Trả về:**
java.lang.Object