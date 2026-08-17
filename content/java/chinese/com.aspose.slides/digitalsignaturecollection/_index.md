---
title: DigitalSignatureCollection
second_title: Aspose.Slides Java API 参考
description: 表示附加到文档的数字签名集合。
type: docs
url: /zh/com.aspose.slides/digitalsignaturecollection/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有已实现的接口:**  
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)  
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

表示附加到文档的数字签名集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的签名。 |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | 在集合末尾添加签名。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的签名。 |
| [clear()](#clear--) | 从集合中删除所有签名。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [size()](#size--) | 返回集合中元素的数量。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否已同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定的数组。 |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

返回指定索引处的签名。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

在集合末尾添加签名。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | 要添加的签名。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

删除指定索引处的签名。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的签名的索引。 |

### clear() {#clear--}
```
public final void clear()
```

从集合中删除所有签名。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

返回遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - 整个集合的 java.util.Iterator。

### size() {#size--}
```
public final int size()
```

返回集合中元素的数量。只读 int。

**返回值:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。

**返回值:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回值:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定的数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |