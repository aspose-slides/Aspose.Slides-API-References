---
title: ISensitivityLabelCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示套用於文件的敏感度標籤集合。
type: docs
url: /zh-hant/com.aspose.slides/isensitivitylabelcollection/
---
**全部已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

表示套用於文件的敏感度標籤集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據索引傳回敏感度標籤。 |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | 在集合的末端新增敏感度標籤。 |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | 將 SensitivityLabel 新增至集合。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的敏感度標籤。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [getCount()](#getCount--) | 取得集合中所有元素的數量。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

依索引傳回敏感度標籤。唯讀 [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

在集合的末端新增敏感度標籤。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | java.lang.String | 敏感度標籤的 ID。 |
| siteId | java.util.UUID | Azure Active Directory（Azure AD）站台識別碼。 |
| isEnabled | boolean | 指示是否啟用該敏感度標籤的旗標。 |
| methodType | int | 敏感度標籤的指派方式。 |

**傳回值：**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

將 SensitivityLabel 新增至集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | 要在集合末端新增的 SensitivityLabel 物件。 |

**傳回值：**
int - SensitivityLabel 被新增的索引位置。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除指定索引處的敏感度標籤。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 應刪除之敏感度標籤的索引。 |
### clear() {#clear--}
```
public abstract void clear()
```

從集合中移除所有元素。
### getCount() {#getCount--}
```
public abstract int getCount()
```

取得集合中所有元素的數量。唯讀  int 。

**傳回值：**
int