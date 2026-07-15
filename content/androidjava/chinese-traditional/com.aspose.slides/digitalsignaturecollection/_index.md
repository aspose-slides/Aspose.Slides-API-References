---
title: DigitalSignatureCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 代表一個附加於文件的數位簽章集合。
type: docs
url: /zh-hant/com.aspose.slides/digitalsignaturecollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有實作的介面：**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

代表一個附加於文件的數位簽章集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回索引處的簽章。 |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | 在集合末端加入簽章。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的簽章。 |
| [clear()](#clear--) | 移除集合中的所有簽章。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [size()](#size--) | 傳回集合中元素的數量。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```


傳回索引處的簽章。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```


在集合末端加入簽章。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | 要加入的簽章。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除指定索引處的簽章。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 應刪除之簽章的索引。 |

### clear() {#clear--}
```
public final void clear()
```


移除集合中的所有簽章。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```


傳回用於遍歷集合的列舉器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```


傳回整個集合的 java 迭代器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - 整個集合的 java.util.Iterator。
### size() {#size--}
```
public final int size()
```


傳回集合中元素的數量。唯讀 int。

**傳回值：**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 boolean。

**傳回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


傳回同步根。唯讀 Object。

**傳回值：**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |