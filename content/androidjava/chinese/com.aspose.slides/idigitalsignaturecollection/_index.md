---
title: IDigitalSignatureCollection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示附加到文档的数字签名集合。
type: docs
url: /zh/com.aspose.slides/idigitalsignaturecollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

表示附加到文档的数字签名集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引的签名。 |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | 在集合末尾添加签名。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引的签名。 |
| [clear()](#clear--) | 从集合中移除所有签名。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

返回指定索引的签名。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Signature to add. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the signature at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the signature that should be deleted. |

### clear() {#clear--}
```
public abstract void clear()


Removes all signatures from collection.

