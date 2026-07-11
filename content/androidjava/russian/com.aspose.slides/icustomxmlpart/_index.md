---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Represents custom xml part.
type: docs
url: /ru/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Представляет пользовательскую XML часть.
## Методы

| Метод | Описание |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Возвращает или задает XML данные в виде строки UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Возвращает или задает XML данные в виде строки UTF-8. |
| [getXmlData()](#getXmlData--) | Возвращает или задает XML данные. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Возвращает или задает XML данные. |
| [getItemId()](#getItemId--) | Указывает глобально уникальный идентификатор (GUID), который однозначно определяет одну пользовательскую XML часть в документе Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Указывает глобально уникальный идентификатор (GUID), который однозначно определяет одну пользовательскую XML часть в документе Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Возвращает набор XML схем, связанных с пользовательской XML частью. |
| [remove()](#remove--) | Удаляет пользовательскую XML часть из презентации. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Возвращает или задает XML данные в виде строки UTF-8. Чтение/запись String.

**Возвращает:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Возвращает или задает XML данные в виде строки UTF-8. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Возвращает или задает XML данные. Чтение/запись byte[].

**Возвращает:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Возвращает или задает XML данные. Чтение/запись byte[].

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Указывает глобально уникальный идентификатор (GUID), который однозначно определяет одну пользовательскую XML часть в документе Office Open XML. Только для чтения java.util.UUID.

**Возвращает:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Указывает глобально уникальный идентификатор (GUID), который однозначно определяет одну пользовательскую XML часть в документе Office Open XML. Только для чтения java.util.UUID.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Возвращает набор XML схем, связанных с пользовательской XML частью. Только для чтения String[].

**Возвращает:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Удаляет пользовательскую XML часть из презентации.