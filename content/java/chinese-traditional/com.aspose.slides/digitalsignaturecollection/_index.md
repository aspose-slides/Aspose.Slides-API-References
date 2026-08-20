---
title: DigitalSignatureCollection
second_title: Aspose.Slides for Java API 參考
description: 表示附加於文件的數位簽名集合。
type: docs
url: /zh-hant/com.aspose.slides/digitalsignaturecollection/
---
**繼承關係:**
java.lang.Object, com.aspose.slides.DomObject

**已實作的介面:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

表示附加於文件的數位簽名集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回依索引取得的簽名。 |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | 將簽名加入於集合的末端。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的簽名。 |
| [clear()](#clear--) | 從集合中移除所有簽名。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉子。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [size()](#size--) | 傳回集合中元素的數量。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否已同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中所有元素複製到指定的陣列。 |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```


傳回依索引取得的簽名。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```


將簽名加入於集合的末端。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | 要加入的簽名。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除指定索引處的簽名。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 應刪除的簽名之索引。 |

### clear() {#clear--}
```
public final void clear()
```


從集合中移除所有簽名。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```


傳回用於遍歷集合的列舉子。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```


傳回整個集合的 java 迭代器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```


傳回集合中元素的數量。唯讀 int.

**傳回值:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


傳回指示集合存取是否已同步（執行緒安全）的值。唯讀 boolean.

**傳回值:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


傳回同步根。唯讀 Object.

**傳回值:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


將集合中所有元素複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |