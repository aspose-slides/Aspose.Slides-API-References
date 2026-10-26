---
title: ISensitivityLabelCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 代表套用於文件的敏感度標籤集合。
type: docs
url: /zh-hant/com.aspose.slides/isensitivitylabelcollection/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

代表套用於文件的敏感度標籤集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 依索引傳回敏感度標籤。 |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | 在集合的末端加入敏感度標籤。 |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | 向集合加入 SensitivityLabel。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的敏感度標籤。 |
| [clear()](#clear--) | 移除集合中的所有元素。 |
| [getCount()](#getCount--) | 取得集合中所有元素的數量。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


依索引傳回敏感度標籤。唯讀 [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**回傳值：**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


在集合的末端加入敏感度標籤。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| id | java.lang.String | 敏感度標籤的 id。 |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) 站點識別碼。 |
| isEnabled | boolean | 指示敏感度標籤是否啟用的旗標。 |
| methodType | int | 敏感度標籤的指派方法。 |

**回傳值：**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```


向集合加入 SensitivityLabel。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | 要在集合末端加入的 SensitivityLabel 物件。 |

**回傳值：**
int - 新加入的 SensitivityLabel 所在的索引。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除指定索引處的敏感度標籤。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 應刪除的敏感度標籤之索引。 |

### clear() {#clear--}
```
public abstract void clear()
```


移除集合中的所有元素。

### getCount() {#getCount--}
```
public abstract int getCount()
```


取得集合中所有元素的數量。唯讀 int 。

**回傳值：**
int