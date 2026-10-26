---
title: SensitivityLabel
second_title: Справочник API Aspose.Slides для Java
description: Представляет метку конфиденциальности из Microsoft Purview Information Protection.
type: docs
url: /ru/com.aspose.slides/sensitivitylabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Представляет метку конфиденциальности из Microsoft Purview Information Protection.
## Методы

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Возвращает или задает идентификатор метки конфиденциальности. |
| [setId(String value)](#setId-java.lang.String-) | Возвращает или задает идентификатор метки конфиденциальности. |
| [getSiteId()](#getSiteId--) | Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки конфиденциальности, описывающей метку конфиденциальности. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки конфиденциальности, описывающей метку конфиденциальности. |
| [isEnabled()](#isEnabled--) | Указывает, включена ли метка конфиденциальности. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Указывает, включена ли метка конфиденциальности. |
| [isRemoved()](#isRemoved--) | Указывает, была ли метка конфиденциальности удалена. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Указывает, была ли метка конфиденциальности удалена. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Возвращает или задает метод назначения метки конфиденциальности. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Возвращает или задает метод назначения метки конфиденциальности. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Возвращает список типов маркеров контента, которые должны быть применены к файлу. |
### getId() {#getId--}
```
public final String getId()
```


Возвращает или задает идентификатор метки конфиденциальности. Чтение/запись String.

**Returns:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Возвращает или задает идентификатор метки конфиденциальности. Чтение/запись String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки конфиденциальности, описывающей метку конфиденциальности. Чтение/запись java.util.UUID.

**Returns:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки конфиденциальности, описывающей метку конфиденциальности. Чтение/запись java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Указывает, включена ли метка конфиденциальности.

**Returns:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Указывает, включена ли метка конфиденциальности.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Указывает, была ли метка конфиденциальности удалена.

**Returns:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Указывает, была ли метка конфиденциальности удалена.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Возвращает или задает метод назначения метки конфиденциальности. Чтение/запись [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Returns:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Возвращает или задает метод назначения метки конфиденциальности. Чтение/запись [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Возвращает список типов маркеров контента, которые должны быть применены к файлу.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Список типов контента [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)