---
title: SensitivityLabelCollection
second_title: Aspose.Slides for Java API 參考
description: 表示套用於文件的敏感度標籤集合。
type: docs
url: /zh-hant/com.aspose.slides/sensitivitylabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

表示套用於文件的敏感度標籤集合。
## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 依索引傳回敏感度標籤。 |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | 在集合的末端加入敏感度標籤。 |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | 將 SensitivityLabel 加入集合。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的敏感度標籤。 |
| [clear()](#clear--) | 移除集合中的所有元素。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [getCount()](#getCount--) | 傳回集合中元素的數量。 |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | 將集合中所有元素複製到指定的陣列。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


依索引傳回敏感度標籤。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


在集合的末端加入敏感度標籤。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 敏感度標籤的 id。 |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) 站點識別碼。 |
| isEnabled | boolean | 表示敏感度標籤是否已啟用的旗標。 |
| methodType | int | 敏感度標籤的指派方式。 |

**Returns:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


將 SensitivityLabel 加入集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | 要在集合末端加入的 SensitivityLabel 物件。 |

**Returns:**
int - 新增的 SensitivityLabel 在集合中的索引。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


移除指定索引處的敏感度標籤。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 應該被刪除的敏感度標籤之索引。 |

### clear() {#clear--}
```
public final void clear()
```


移除集合中的所有元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


傳回可遍歷集合的列舉器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - 可用於遍歷集合的  System.Collections.Generic.IEnumerator1。

### getCount() {#getCount--}
```
public final int getCount()
```


傳回集合中元素的數量。唯讀  int 。

**Returns:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


將集合中所有元素複製到指定的陣列。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |