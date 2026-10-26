---
title: ICustomXmlPartCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示自訂 XML 部分的集合。
type: docs
url: /zh-hant/com.aspose.slides/icustomxmlpartcollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

表示自訂 XML 部分的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的元素。 |
| [add(byte[] xmlData)](#add-byte---) | 新增自訂 XML 部分。 |
| [add(String xmlString)](#add-java.lang.String-) | 新增自訂 XML 部分。 |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | 新增自訂 XML 部分。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的自訂 XML 部分。 |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | 從集合中移除特定物件的第一個出現項目。 |
| [clear()](#clear--) | 從集合中移除所有項目。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```


返回指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要取得的元素之零基索引。 |

**傳回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 指定索引處的元素。
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```


新增自訂 XML 部分。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xmlData | byte[] | 要新增的部件之 XML 資料。 |

**傳回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 已建立的自訂 XML 部分。
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```


新增自訂 XML 部分。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xmlString | java.lang.String | 要新增的部件之 XML 字串。 |

**傳回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 已建立的自訂 XML 部分。
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```


新增自訂 XML 部分。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 包含新部件 XML 資料的 inputStream。 |

**傳回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 已建立的自訂 XML 部分。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除指定索引處的自訂 XML 部分。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的元素之零基索引。 |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```


從集合中移除特定物件的第一個出現項目。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 要移除的自訂 XML 部分。 |

**傳回值：**
boolean - 若成功移除項目則為 true；否則為 false。
### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有項目。