---
title: SensitivityLabelCollection
second_title: Aspose.Slides for Java API 参考
description: 表示应用于文档的敏感性标签集合。
type: docs
url: /zh/com.aspose.slides/sensitivitylabelcollection/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

表示文档中应用的敏感性标签集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的敏感性标签。 |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | 在集合末尾添加敏感性标签。 |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | 向集合中添加 SensitivityLabel。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的敏感性标签。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [getCount()](#getCount--) | 返回集合中元素的数量。 |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | 将集合中的所有元素复制到指定数组。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

返回指定索引处的敏感性标签。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

在集合末尾添加敏感性标签。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 敏感性标签的 id。 |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) 站点标识符。 |
| isEnabled | boolean | 标志，指示敏感性标签是否已启用。 |
| methodType | int | 敏感性标签的分配方法。 |

**返回:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

向集合中添加一个 SensitivityLabel。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | 要添加到集合末尾的 SensitivityLabel 对象。 |

**返回:**
int - 添加 SensitivityLabel 的索引。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

删除指定索引处的敏感性标签。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的敏感性标签的索引。 |
### clear() {#clear--}
```
public final void clear()
```

删除集合中的所有元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

返回遍历集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - 可用于遍历集合的 System.Collections.Generic.IEnumerator1
### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中元素的数量。只读  int 。

**返回:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

将集合中的所有元素复制到指定数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | 目标数组。 |
| index | int | 目标数组中的起始索引。 |