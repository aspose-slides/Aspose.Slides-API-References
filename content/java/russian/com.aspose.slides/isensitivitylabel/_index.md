---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Представляет метку конфиденциальности из Microsoft Purview Information Protection.
type: docs
url: /ru/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Представляет метку конфиденциальности из Microsoft Purview Information Protection.
## Методы

| Метод | Описание |
| --- | --- |
| [getId()](#getId--) | Возвращает или задает идентификатор метки конфиденциальности. |
| [setId(String value)](#setId-java.lang.String-) | Возвращает или задает идентификатор метки конфиденциальности. |
| [getSiteId()](#getSiteId--) | Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки конфиденциальности, описывающей метку конфиденциальности. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки конфиденциальности, описывающей метку конфиденциальности. |
| [isEnabled()](#isEnabled--) | Указывает, включена ли метка конфиденциальности. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Указывает, включена ли метка конфиденциальности. |
| [isRemoved()](#isRemoved--) | Указывает, была ли удалена метка конфиденциальности. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Указывает, была ли удалена метка конфиденциальности. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Возвращает или задает метод назначения метки конфиденциальности. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Возвращает или задает метод назначения метки конфиденциальности. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Возвращает список типов маркировки контента, которые должны быть применены к файлу. |
### getId() {#getId--}
```
public abstract String getId()
```

Возвращает или задает идентификатор метки конфиденциальности. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Возвращает или задает идентификатор метки конфиденциальности. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки конфиденциальности, описывающей метку конфиденциальности. Чтение/запись java.util.UUID.

**Возвращаемое значение:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Возвращает или задает идентификатор сайта Azure Active Directory (Azure AD), соответствующий политике метки конфиденциальности, описывающей метку конфиденциальности. Чтение/запись java.util.UUID.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

Указывает, включена ли метка конфиденциальности.

**Возвращаемое значение:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

Указывает, включена ли метка конфиденциальности.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

Указывает, была ли удалена метка конфиденциальности.

**Возвращаемое значение:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

Указывает, была ли удалена метка конфиденциальности.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

Возвращает или задает метод назначения метки конфиденциальности. Чтение/запись [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Возвращаемое значение:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

Возвращает или задает метод назначения метки конфиденциальности. Чтение/запись [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Возвращает список типов маркировки контента, которые должны быть применены к файлу.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)