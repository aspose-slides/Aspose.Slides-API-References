---
title: DigitalSignatureCollection
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Biểu diễn một tập hợp các chữ ký số được đính kèm vào tài liệu.
type: docs
url: /vi/com.aspose.slides/digitalsignaturecollection/
---
**Kế thừa:**  
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**  
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)  
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

Biểu diễn một tập hợp các chữ ký số được đính kèm vào tài liệu.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về chữ ký theo chỉ mục. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | Thêm chữ ký vào cuối tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa chữ ký tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả chữ ký khỏi tập hợp. |
| [iterator()](#iterator--) | Trả về một enumerator để lặp qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ tập hợp. |
| [size()](#size--) | Trả về số phần tử trong tập hợp. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết liệu việc truy cập vào tập hợp có được đồng bộ (an toàn với các luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp sang mảng được chỉ định. |

### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

Trả về chữ ký theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)

### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

Thêm chữ ký vào cuối tập hợp.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Chữ ký để thêm. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa chữ ký tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của chữ ký cần xóa. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả chữ ký khỏi tập hợp.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

Trả về một enumerator để lặp qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

Trả về một iterator java cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - An java.util.Iterator for the entire collection.

### size() {#size--}
```
public final int size()
```

Trả về số phần tử trong tập hợp. int chỉ đọc.

**Trả về:**
int

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết liệu việc truy cập vào tập hợp có được đồng bộ (an toàn với các luồng) hay không. boolean chỉ đọc.

**Trả về:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một gốc đồng bộ. Object chỉ đọc.

**Trả về:**
java.lang.Object

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ tập hợp sang mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |