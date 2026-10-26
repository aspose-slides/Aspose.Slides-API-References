---
title: CustomXmlPart
second_title: Справочник API Aspose.Slides для Android на Java
description: Представляет пользовательскую XML-часть.
type: docs
url: /ru/com.aspose.slides/customxmlpart/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Представляет пользовательскую XML-часть.
## Методы

| Метод | Описание |
| --- | --- |
| [getXmlData()](#getXmlData--) | Возвращает или задает xml-данные. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Возвращает или задает xml-данные. |
| [getXmlAsString()](#getXmlAsString--) | Возвращает или задает xml-данные как строку UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Возвращает или задает xml-данные как строку UTF-8. |
| [getItemId()](#getItemId--) | Указывает глобальный уникальный идентификатор (GUID), который однозначно идентифицирует отдельную пользовательскую XML-часть в документе Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Указывает глобальный уникальный идентификатор (GUID), который однозначно идентифицирует отдельную пользовательскую XML-часть в документе Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Возвращает коллекцию XML-схем, связанных с пользовательской XML-частью. |
| [remove()](#remove--) | Удаляет пользовательскую XML-часть из презентации. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

Возвращает или задает xml-данные. Чтение/запись byte[].

**Возвращает:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

Возвращает или задает xml-данные. Чтение/запись byte[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

Возвращает или задает xml-данные как строку UTF-8. Чтение/запись String.

**Возвращает:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

Возвращает или задает xml-данные как строку UTF-8. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Указывает глобальный уникальный идентификатор (GUID), который однозначно идентифицирует отдельную пользовательскую XML-часть в документе Office Open XML. Только для чтения java.util.UUID.

**Возвращает:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Указывает глобальный уникальный идентификатор (GUID), который однозначно идентифицирует отдельную пользовательскую XML-часть в документе Office Open XML. Только для чтения java.util.UUID.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Возвращает коллекцию XML-схем, связанных с пользовательской XML-частью. Только для чтения String[].

**Возвращает:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Удаляет пользовательскую XML-часть из презентации.