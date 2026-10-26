---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /zh-hant/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

表示來自 Microsoft Purview Information Protection 的敏感度標籤。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getId()](#getId--) | 返回或設定敏感度標籤的 ID。 |
| [setId(String value)](#setId-java.lang.String-) | 返回或設定敏感度標籤的 ID。 |
| [getSiteId()](#getSiteId--) | 返回或設定與描述此敏感度標籤之敏感度標籤原則相對應的 Azure Active Directory (Azure AD) 站點識別碼。 |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | 返回或設定與描述此敏感度標籤之敏感度標籤原則相對應的 Azure Active Directory (Azure AD) 站點識別碼。 |
| [isEnabled()](#isEnabled--) | 指示此敏感度標籤是否已啟用。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 指示此敏感度標籤是否已啟用。 |
| [isRemoved()](#isRemoved--) | 指示此敏感度標籤是否已移除。 |
| [setRemoved(boolean value)](#setRemoved-boolean-) | 指示此敏感度標籤是否已移除。 |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | 返回或設定此敏感度標籤的指派方法。 |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | 返回或設定此敏感度標籤的指派方法。 |
| [getContentMarkTypes()](#getContentMarkTypes--) | 返回應套用於檔案的內容標記類型清單。 |

### getId() {#getId--}
```
public abstract String getId()
```

返回或設定敏感度標籤的 ID。讀寫 String。

**返回：**
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

返回或設定敏感度標籤的 ID。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

返回或設定與描述此敏感度標籤之敏感度標籤原則相對應的 Azure Active Directory (Azure AD) 站點識別碼。讀寫 java.util.UUID。

**返回：**
java.util.UUID

### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

返回或設定與描述此敏感度標籤之敏感度標籤原則相對應的 Azure Active Directory (Azure AD) 站點識別碼。讀寫 java.util.UUID。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

指示此敏感度標籤是否已啟用。

**返回：**
boolean

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

指示此敏感度標籤是否已啟用。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

指示此敏感度標籤是否已移除。

**返回：**
boolean

### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

指示此敏感度標籤是否已移除。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

返回或設定此敏感度標籤的指派方法。讀寫 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**返回：**
int

### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

返回或設定此敏感度標籤的指派方法。讀寫 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

返回應套用於檔案的內容標記類型清單。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)