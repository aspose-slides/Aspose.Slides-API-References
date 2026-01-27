---
title: SensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /com.aspose.slides/sensitivitylabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Represents the sensitivity label from Microsoft Purview Information Protection.
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Returns or sets the id of sensitivity label. |
| [setId(String value)](#setId-java.lang.String-) | Returns or sets the id of sensitivity label. |
| [getSiteId()](#getSiteId--) | Returns or sets the Azure Active Directory (Azure AD) site identifier corresponding to the sensitivity label policy which describes the sensitivity label. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Returns or sets the Azure Active Directory (Azure AD) site identifier corresponding to the sensitivity label policy which describes the sensitivity label. |
| [isEnabled()](#isEnabled--) | Indicates whether the sensitivity label is enabled. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indicates whether the sensitivity label is enabled. |
| [isRemoved()](#isRemoved--) | Indicates whether the sensitivity label was removed. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indicates whether the sensitivity label was removed. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Returns or sets the assignment method for the sensitivity label. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Returns or sets the assignment method for the sensitivity label. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Returns the list of types of content marking that ought to be applied to a file. |
### getId() {#getId--}
```
public final String getId()
```


Returns or sets the id of sensitivity label. Read/write String.

**Returns:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Returns or sets the id of sensitivity label. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Returns or sets the Azure Active Directory (Azure AD) site identifier corresponding to the sensitivity label policy which describes the sensitivity label. Read/write java.util.UUID.

**Returns:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Returns or sets the Azure Active Directory (Azure AD) site identifier corresponding to the sensitivity label policy which describes the sensitivity label. Read/write java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Indicates whether the sensitivity label is enabled.

**Returns:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Indicates whether the sensitivity label is enabled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Indicates whether the sensitivity label was removed.

**Returns:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Indicates whether the sensitivity label was removed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Returns or sets the assignment method for the sensitivity label. Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Returns:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Returns or sets the assignment method for the sensitivity label. Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Returns the list of types of content marking that ought to be applied to a file.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)
