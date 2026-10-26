---
title: ISensitivityLabelCollection
second_title: Aspose.Slides for Java API 参考
description: 表示文档中已应用的敏感度标签的集合。
type: docs
url: /zh/com.aspose.slides/isensitivitylabelcollection/
---
**所有已实现的接口:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

表示文档中已应用的敏感度标签的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 按索引返回敏感度标签。 |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | 在集合末尾添加敏感度标签。 |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | 将 SensitivityLabel 添加到集合中。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引处的敏感度标签。 |
| [clear()](#clear--) | 移除集合中的所有元素。 |
| [getCount()](#getCount--) | 获取集合中所有元素的数量。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

按索引返回敏感度标签。只读 [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

在集合末尾添加敏感度标签。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 敏感度标签的 id。 |
| siteId | java.util.UUID | Azure Active Directory（Azure AD）站点标识符。 |
| isEnabled | boolean | 标志表示该敏感度标签是否已启用。 |
| methodType | int | 敏感度标签的分配方法。 |

**返回值：**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

将 SensitivityLabel 添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | 要在集合末尾添加的 SensitivityLabel 对象。 |

**返回值：**
int - SensitivityLabel 添加到的索引。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除指定索引处的敏感度标签。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的敏感度标签的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除集合中的所有元素。

### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合中所有元素的数量。只读  int 。

**返回值：**
int