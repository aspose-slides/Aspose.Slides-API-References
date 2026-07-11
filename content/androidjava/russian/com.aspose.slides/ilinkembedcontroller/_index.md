---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Интерактивный интерфейс обратного вызова, используемый для определения того, как объект должен обрабатываться при сохранении.
type: docs
url: /ru/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

Интерфейс обратного вызова, используемый для определения того, как объект должен обрабатываться при сохранении.
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Определяет, где объект должен быть сохранён. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Возвращает URL внешнего объекта. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Сохраняет внешний объект. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


Определяет, где объект должен быть сохранён. Этот метод вызывается один раз для каждого идентификатора объекта. Не гарантируется, что не будет двух объектов с одинаковыми данными, semanticName и contentType, но разными id.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | int | Идентификатор объекта. Этот id уникален в пределах операции сохранения. |
| entityData | byte[] | Двоичные данные объекта. Этот параметр может быть null, если двоичные данные объекта ещё не сгенерированы. |
| semanticName | java.lang.String | Краткий текст, описывающий смысл объекта. Контроллер может использовать его как часть имени внешнего объекта, но обеспечение уникальности имён и допустимых символов остаётся за диспетчером. |
| contentType | java.lang.String | MIME-тип объекта. |
| recomendedExtension | java.lang.String | Расширение имени файла, рекомендованное для этого MIME-типа. |

**Возвращаемое значение:**
int - Decision
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


Возвращает URL внешнего объекта. Этот метод всегда вызывается, если \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) вернул [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) и может быть вызван, если \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) вернул [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed), но внедрение невозможно. Может быть вызван несколько раз для одного и того же id объекта.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | int | Идентификатор объекта. Этот id уникален в пределах операции сохранения. |
| referrer | int | Идентификатор ссылающегося объекта или 0, если объект ссылается корневой документ. Может использоваться для генерации относительной ссылки. |

**Возвращаемое значение:**
java.lang.String - Url внешнего объекта или null, если этот объект следует игнорировать.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


Сохраняет внешний объект.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | int | Идентификатор объекта. Этот id уникален в пределах операции сохранения. |
| entityData | byte[] | Двоичные данные объекта. Этот параметр не может быть null. |