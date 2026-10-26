---
title: ICustomXmlPartCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示自定义 XML 部件的集合。
type: docs
url: /zh/com.aspose.slides/icustomxmlpartcollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

表示自定义 XML 部件的集合。
## 方法

| 方法 | 说明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的元素。 |
| [add(byte[] xmlData)](#add-byte---) | 添加新的自定义 XML 部件。 |
| [add(String xmlString)](#add-java.lang.String-) | 添加新的自定义 XML 部件。 |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | 添加新的自定义 XML 部件。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的自定义 XML 部件。 |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | 从集合中删除特定对象的第一次出现。 |
| [clear()](#clear--) | 删除集合中的所有项。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

返回指定索引处的元素。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int | 要获取的元素的零基索引。 |

**返回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 指定索引处的元素。
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

添加新的自定义 XML 部件。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| xmlData | byte[] | 要添加的新部件的 XML 数据。 |

**返回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 创建的自定义 XML 部件。
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

添加新的自定义 XML 部件。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| xmlString | java.lang.String | 要添加的新部件的 XML 字符串。 |

**返回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 创建的自定义 XML 部件。
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

添加新的自定义 XML 部件。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 包含新部件 XML 数据的输入流。 |

**返回值：**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - 创建的自定义 XML 部件。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除指定索引处的自定义 XML 部件。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int | 要删除的元素的零基索引。 |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

删除集合中指定对象的第一次出现。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | 要删除的自定义 XML 部件。 |

**返回值：**
boolean - 若成功删除项则返回 true；否则返回 false。
### clear() {#clear--}
```
public abstract void clear()
```

删除所有项。