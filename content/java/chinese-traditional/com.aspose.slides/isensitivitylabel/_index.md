---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API 參考
description: 代表 Microsoft Purview Information Protection 中的敏感性標籤。
type: docs
url: /zh-hant/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

代表 Microsoft Purview Information Protection 中的敏感性標籤。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getId()](#getId--) | 返回或設定敏感性標籤的 id。 |
| [setId(String value)](#setId-java.lang.String-) | 返回或設定敏感性標籤的 id。 |
| [getSiteId()](#getSiteId--) | 返回或設定 Azure Active Directory (Azure AD) 站點識別碼，以對應描述此敏感性標籤的標籤原則。 |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | 返回或設定 Azure Active Directory (Azure AD) 站點識別碼，以對應描述此敏感性標籤的標籤原則。 |
| [isEnabled()](#isEnabled--) | 表示敏感性標籤是否已啟用。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 表示敏感性標籤是否已啟用。 |
| [isRemoved()](#isRemoved--) | 表示敏感性標籤是否已被移除。 |
| [setRemoved(boolean value)](#setRemoved-boolean-) | 表示敏感性標籤是否已被移除。 |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | 返回或設定敏感性標籤的指派方法。 |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | 返回或設定敏感性標籤的指派方法。 |
| [getContentMarkTypes()](#getContentMarkTypes--) | 返回應套用於檔案的內容標記類型清單。 |
### getId() {#getId--}
```
public abstract String getId()
```

返回或設定敏感性標籤的 id。讀/寫 String。

**Returns:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

返回或設定敏感性標籤的 id。讀/寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

返回或設定 Azure Active Directory (Azure AD) 站點識別碼，以對應描述此敏感性標籤的標籤原則。讀/寫 java.util.UUID。

**Returns:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

返回或設定 Azure Active Directory (Azure AD) 站點識別碼，以對應描述此敏感性標籤的標籤原則。讀/寫 java.util.UUID。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

表示敏感性標籤是否已啟用。

**Returns:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

表示敏感性標籤是否已啟用。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

表示敏感性標籤是否已被移除。

**Returns:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

表示敏感性標籤是否已被移除。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

返回或設定敏感性標籤的指派方法。讀/寫 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**Returns:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

返回或設定敏感性標籤的指派方法。讀/寫 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

返回應套用於檔案的內容標記類型清單。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)