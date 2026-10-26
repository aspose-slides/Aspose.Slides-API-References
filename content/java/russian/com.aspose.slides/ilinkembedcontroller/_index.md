---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /ru/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Интерфейс обратного вызова, используемый для определения того, как объект должен обрабатываться при сохранении.

## Методы

| Метод | Описание |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Определяет, где объект должен храниться. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Возвращает URL внешнего объекта. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Сохраняет внешний объект. |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Определяет, где объект должен храниться. Этот метод вызывается один раз для каждого идентификатора объекта. Не гарантируется, что не будет двух объектов с одинаковыми данными, semanticName и contentType, но разными идентификаторами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | int | Идентификатор объекта. Этот идентификатор уникален в рамках операции сохранения. |
| entityData | byte[] | Бинарные данные объекта. Этот параметр может быть null, если бинарные данные объекта еще не созданы. |
| semanticName | java.lang.String | Краткий текст, описывающий смысл объекта. Контроллер может использовать его как часть имени внешнего объекта, но обеспечение уникальности имен и использование только разрешённых символов лежит на диспетчере. |
| contentType | java.lang.String | MIME-тип объекта. |
| recomendedExtension | java.lang.String | Расширение имени файла, рекомендованное для этого MIME-типа. |

**Возвращаемое значение:**
int - Decision

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

Возвращает URL внешнего объекта. Этот метод всегда вызывается, если \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) вернул [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) и может быть вызван, если \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) вернул [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed), но внедрение невозможно. Может вызываться несколько раз для одного и того же идентификатора объекта.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | int | Идентификатор объекта. Этот идентификатор уникален в рамках операции сохранения. |
| referrer | int | Идентификатор ссылающегося объекта или 0, если объект ссылается корневой документ. Может использоваться для генерации относительной ссылки. |

**Возвращаемое значение:**
java.lang.String - URL внешнего объекта или null, если этот объект следует игнорировать.

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

Сохраняет внешний объект.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | int | Идентификатор объекта. Этот идентификатор уникален в рамках операции сохранения. |
| entityData | byte[] | Бинарные данные объекта. Этот параметр не может быть null. |