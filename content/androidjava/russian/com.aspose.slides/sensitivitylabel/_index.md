---
title: SensitivityLabel
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет метку чувствительности из Microsoft Purview Information Protection.
type: docs
url: /ru/com.aspose.slides/sensitivitylabel/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Представляет метку чувствительности из Microsoft Purview Information Protection.
## Методы

| Метод | Описание |
| --- | --- |
| [getId()](#getId--) | Возвращает или задает идентификатор метки чувствительности. |
| [setId(String value)](#setId-java.lang.String-) | Возвращает или задает идентификатор метки чувствительности. |
| [getSiteId()](#getSiteId--) | Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки чувствительности, описывающей метку чувствительности. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки чувствительности, описывающей метку чувствительности. |
| [isEnabled()](#isEnabled--) | Указывает, включена ли метка чувствительности. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Указывает, включена ли метка чувствительности. |
| [isRemoved()](#isRemoved--) | Указывает, была ли метка чувствительности удалена. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Указывает, была ли метка чувствительности удалена. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Возвращает или задает метод назначения для метки чувствительности. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Возвращает или задает метод назначения для метки чувствительности. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Возвращает список типов маркировки содержимого, которые следует применить к файлу. |
### getId() {#getId--}
```
public final String getId()
```


Возвращает или задает идентификатор метки чувствительности. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Возвращает или задает идентификатор метки чувствительности. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки чувствительности, описывающей метку чувствительности. Чтение/запись java.util.UUID.

**Возвращаемое значение:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки чувствительности, описывающей метку чувствительности. Чтение/запись java.util.UUID.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Указывает, включена ли метка чувствительности.

**Возвращаемое значение:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Указывает, включена ли метка чувствительности.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Указывает, была ли метка чувствительности удалена.

**Возвращаемое значение:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Указывает, была ли метка чувствительности удалена.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Возвращает или задает метод назначения для метки чувствительности. Чтение/запись [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Возвращаемое значение:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Возвращает или задает метод назначения для метки чувствительности. Чтение/запись [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Возвращает список типов маркировки содержимого, которые следует применить к файлу.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Список типов содержимого [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)