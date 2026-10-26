---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /zh/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

表示来自 Microsoft Purview 信息保护的敏感度标签。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getId()](#getId--) | 返回或设置敏感度标签的 id。 |
| [setId(String value)](#setId-java.lang.String-) | 返回或设置敏感度标签的 id。 |
| [getSiteId()](#getSiteId--) | 返回或设置对应于描述敏感度标签的敏感度标签策略的 Azure Active Directory (Azure AD) 站点标识符。 |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | 返回或设置对应于描述敏感度标签的敏感度标签策略的 Azure Active Directory (Azure AD) 站点标识符。 |
| [isEnabled()](#isEnabled--) | 指示该敏感度标签是否已启用。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 指示该敏感度标签是否已启用。 |
| [isRemoved()](#isRemoved--) | 指示该敏感度标签是否已被移除。 |
| [setRemoved(boolean value)](#setRemoved-boolean-) | 指示该敏感度标签是否已被移除。 |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | 返回或设置敏感度标签的分配方法。 |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | 返回或设置敏感度标签的分配方法。 |
| [getContentMarkTypes()](#getContentMarkTypes--) | 返回应应用于文件的内容标记类型列表。 |

### getId() {#getId--}
```
public abstract String getId()
```

返回或设置敏感度标签的 id。**读/写** String。

**返回:**
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

返回或设置敏感度标签的 id。**读/写** String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

返回或设置对应于描述敏感度标签的敏感度标签策略的 Azure Active Directory (Azure AD) 站点标识符。**读/写** java.util.UUID。

**返回:**
java.util.UUID

### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

返回或设置对应于描述敏感度标签的敏感度标签策略的 Azure Active Directory (Azure AD) 站点标识符。**读/写** java.util.UUID。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

指示该敏感度标签是否已启用。

**返回:**
boolean

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

指示该敏感度标签是否已启用。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

指示该敏感度标签是否已被移除。

**返回:**
boolean

### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

指示该敏感度标签是否已被移除。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

返回或设置敏感度标签的分配方法。**读/写** [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**返回:**
int

### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

返回或设置敏感度标签的分配方法。**读/写** [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

返回应应用于文件的内容标记类型列表。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - 内容类型列表 [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)