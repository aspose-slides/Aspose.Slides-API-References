---
title: SensitivityLabelCollection
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示套用於文件的敏感度標籤集合。
type: docs
url: /zh-hant/com.aspose.slides/sensitivitylabelcollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**已實作的所有介面：**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

表示套用於文件的敏感度標籤集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回索引處的敏感度標籤。 |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | 在集合的末尾新增敏感度標籤。 |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | 將 SensitivityLabel 新增至集合中。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的敏感度標籤。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [iterator()](#iterator--) | 返回可遍歷集合的列舉器。 |
| [getCount()](#getCount--) | 返回集合中元素的數量。 |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | 將集合中所有元素複製到指定的陣列。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

返回索引處的敏感度標籤。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

在集合的末尾新增敏感度標籤。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 敏感度標籤的 id。 |
| siteId | java.util.UUID | Azure Active Directory（Azure AD）站點識別碼。 |
| isEnabled | boolean | 旗標表示是否已啟用此敏感度標籤。 |
| methodType | int | 敏感度標籤的指派方法。 |

**返回值：**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

將 SensitivityLabel 新增至集合中。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | 要在集合末尾新增的 SensitivityLabel 物件。 |

**返回值：**
int - SensitivityLabel 被新增的索引位置。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除指定索引處的敏感度標籤。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 應刪除之敏感度標籤的索引。 |
### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有元素。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

返回可遍歷集合的列舉器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - 可用於遍歷集合的 System.Collections.Generic.IEnumerator1。
### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中元素的數量。唯讀  int 。

**返回值：**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |