---
title: IDigitalSignatureCollection
second_title: Aspose.Slides for Java API 參考
description: 表示附加於文件的數位簽章集合。
type: docs
url: /zh-hant/com.aspose.slides/idigitalsignaturecollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

表示附加於文件的數位簽章集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回依索引的簽章。 |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | 將簽章新增至集合的末端。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的簽章。 |
| [clear()](#clear--) | 移除集合中的所有簽章。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


傳回依索引的簽章。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```


將簽章新增至集合的末端。

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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | 要新增的簽章。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除指定索引處的簽章。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 應刪除之簽章的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```


移除集合中的所有簽章。