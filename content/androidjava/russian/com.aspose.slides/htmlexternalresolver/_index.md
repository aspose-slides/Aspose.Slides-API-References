---
title: HtmlExternalResolver
second_title: Aspose.Slides для Android через справочник Java API
description: Объект обратного вызова, используемый процедурой импорта HTML для получения связанных объектов, таких как изображения.
type: docs
url: /ru/com.aspose.slides/htmlexternalresolver/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Объект обратного вызова, используемый процедурой импорта HTML для получения связанных объектов, например изображений.

--------------------

Использование этого резольвера может создать уязвимость, когда предоставленный клиентом HTML-файл заставит серверное программное обеспечение получать локальный или сетевой файл. Используйте с осторожностью. Рекомендуется вовсе не указывать HtmlExternalResolver (будут считываться только встроенные объекты) или создать подкласс, который проверяет, является ли указанный URI действительным.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Разрешает абсолютный URI из базового и относительного URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Соотносит URI с объектом, содержащим реальный ресурс. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Разрешает абсолютный URI из базового и относительного URI.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | java.lang.String | Базовый URI объектов-ссылок |
| relativeUri | java.lang.String | Относительный URI к связанному объекту. |

**Возвращаемое значение:**
java.lang.String - Абсолютный URI или null, если относительный URI нельзя разрешить.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Соотносит URI с объектом, содержащим реальный ресурс.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | java.lang.String | Абсолютный URI к объекту. |

**Возвращаемое значение:**
java.io.InputStream - Объект InputStream или null, если ресурс нельзя передать потоком.