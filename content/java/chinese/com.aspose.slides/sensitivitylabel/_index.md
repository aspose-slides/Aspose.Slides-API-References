---
title: SensitivityLabel
second_title: Aspose.Slides for Java API 参考
description: 表示来自 Microsoft Purview Information Protection 的敏感度标签。
type: docs
url: /zh/com.aspose.slides/sensitivitylabel/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)  
```
public final class SensitivityLabel implements ISensitivityLabel
```

表示来自 Microsoft Purview Information Protection 的敏感度标签。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getId()](#getId--) | 返回或设置敏感度标签的 id。 |
| [setId(String value)](#setId-java.lang.String-) | 返回或设置敏感度标签的 id。 |
| [getSiteId()](#getSiteId--) | 返回或设置 Azure Active Directory (Azure AD) 站点标识符，对应描述敏感度标签的敏感度标签策略。 |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | 返回或设置 Azure Active Directory (Azure AD) 站点标识符，对应描述敏感度标签的敏感度标签策略。 |
| [isEnabled()](#isEnabled--) | 指示敏感度标签是否已启用。 |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 指示敏感度标签是否已启用。 |
| [isRemoved()](#isRemoved--) | 指示敏感度标签是否已被移除。 |
| [setRemoved(boolean value)](#setRemoved-boolean-) | 指示敏感度标签是否已被移除。 |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | 返回或设置敏感度标签的分配方法。 |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | 返回或设置敏感度标签的分配方法。 |
| [getContentMarkTypes()](#getContentMarkTypes--) | 返回应应用于文件的内容标记类型列表。 |

### getId() {#getId--}
```
public final String getId()
```

返回或设置敏感度标签的 id。读/写 String.

**返回:**  
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

返回或设置敏感度标签的 id。读/写 String.

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

返回或设置 Azure Active Directory (Azure AD) 站点标识符，对应描述敏感度标签的敏感度标签策略。读/写 java.util.UUID。

**返回:**  
java.util.UUID

### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

返回或设置 Azure Active Directory (Azure AD) 站点标识符，对应描述敏感度标签的敏感度标签策略。读/写 java.util.UUID。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

指示敏感度标签是否已启用。

**返回:**  
boolean

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

指示敏感度标签是否已启用。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

指示敏感度标签是否已被移除。

**返回:**  
boolean

### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

指示敏感度标签是否已被移除。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

返回或设置敏感度标签的分配方法。读/写 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**返回:**  
int

### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

返回或设置敏感度标签的分配方法。读/写 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

返回应应用于文件的内容标记类型列表。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - 内容类型列表 [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)