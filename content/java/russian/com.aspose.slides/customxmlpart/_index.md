---
title: CustomXmlPart
second_title: Aspose.Slides для Java справочник API
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
| [getXmlData()](#getXmlData--) | Возвращает или устанавливает XML-данные. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Возвращает или устанавливает XML-данные. |
| [getXmlAsString()](#getXmlAsString--) | Возвращает или устанавливает XML-данные в виде строки UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Возвращает или устанавливает XML-данные в виде строки UTF-8. |
| [getItemId()](#getItemId--) | Указывает глобально уникальный идентификатор (GUID), который однозначно идентифицирует отдельный пользовательский XML-раздел в документе Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Указывает глобально уникальный идентификатор (GUID), который однозначно идентифицирует отдельный пользовательский XML-раздел в документе Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Возвращает коллекцию XML-схем, связанных с пользовательской XML-частью. |
| [remove()](#remove--) | Удаляет пользовательскую XML-часть из презентации. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

Возвращает или устанавливает XML-данные. Чтение/запись byte[].

**Возвращаемое значение:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

Возвращает или устанавливает XML-данные. Чтение/запись byte[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

Возвращает или устанавливает XML-данные в виде строки UTF-8. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

Возвращает или устанавливает XML-данные в виде строки UTF-8. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Указывает глобально уникальный идентификатор (GUID), который однозначно идентифицирует отдельный пользовательский XML-раздел в документе Office Open XML. Только для чтения java.util.UUID.

**Возвращаемое значение:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Указывает глобально уникальный идентификатор (GUID), который однозначно идентифицирует отдельный пользовательский XML-раздел в документе Office Open XML. Только для чтения java.util.UUID.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Возвращает коллекцию XML-схем, связанных с пользовательской XML-частью. Только для чтения String[].

**Возвращаемое значение:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Удаляет пользовательскую XML-часть из презентации.