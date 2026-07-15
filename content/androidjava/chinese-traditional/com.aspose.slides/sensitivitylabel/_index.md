---
title: SensitivityLabel
second_title: Aspose.Slides for Android 透過 Java API 參考文件
description: 代表來自 Microsoft Purview Information Protection 的敏感性標籤。
type: docs
url: /zh-hant/com.aspose.slides/sensitivitylabel/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

代表來自 Microsoft Purview Information Protection 的敏感性標籤。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getId()](#getId--) | 傳回或設定敏感性標籤的 ID。 |
| [setId(String value)](#setId-java.lang.String-) | 傳回或設定敏感性標籤的 ID。 |
| [getSiteId()](#getSiteId--) | 傳回或設定與描述此敏感性標籤的敏感性標籤原則相對應的 Azure Active Directory (Azure AD) 站台識別碼。 |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | 傳回或設定與描述此敏感性標籤的敏感性標籤原則相對應的 Azure Active Directory (Azure AD) 站台識別碼。 |
| [isEnabled()](#isEnabled--) | 指示敏感性標籤是否已啟用。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 指示敏感性標籤是否已啟用。 |
| [isRemoved()](#isRemoved--) | 指示敏感性標籤是否已移除。 |
| [setRemoved(boolean value)](#setRemoved-boolean-) | 指示敏感性標籤是否已移除。 |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | 傳回或設定敏感性標籤的指派方法。 |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | 傳回或設定敏感性標籤的指派方法。 |
| [getContentMarkTypes()](#getContentMarkTypes--) | 傳回應套用於檔案的內容標記類型清單。 |
### getId() {#getId--}
```
public final String getId()
```

傳回或設定敏感性標籤的 ID。Read/write String.

**傳回值：**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

傳回或設定敏感性標籤的 ID。Read/write String.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

傳回或設定與描述此敏感性標籤的敏感性標籤原則相對應的 Azure Active Directory (Azure AD) 站台識別碼。Read/write java.util.UUID.

**傳回值：**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

傳回或設定與描述此敏感性標籤的敏感性標籤原則相對應的 Azure Active Directory (Azure AD) 站台識別碼。Read/write java.util.UUID.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

指示敏感性標籤是否已啟用。

**傳回值：**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

指示敏感性標籤是否已啟用。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

指示敏感性標籤是否已移除。

**傳回值：**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

指示敏感性標籤是否已移除。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

傳回或設定敏感性標籤的指派方法。Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**傳回值：**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

傳回或設定敏感性標籤的指派方法。Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

傳回應套用於檔案的內容標記類型清單。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - 內容類型清單 [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)