---
title: ExternalResourceResolver
second_title: Aspose.Slides для Android через справочник Java API
description: Класс-обратного вызова, используемый для разрешения внешних ресурсов при импорте документов Html и Svg.
type: docs
url: /ru/com.aspose.slides/externalresourceresolver/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Класс-обратного вызова, используемый для разрешения внешних ресурсов при импорте документов Html, Svg.

--------------------

Использование этого резольвера может создать уязвимость, когда предоставленный клиентом HTML- или SVG-файл заставит серверное программное обеспечение получить локальный или сетевой файл. Используйте с осторожностью. Рекомендуется вообще не указывать ExternalResourceResolver (будут читаться только встроенные объекты) или создать подкласс, который проверяет, является ли указанный uri действительным.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Разрешает абсолютный URI из базового и относительного URI.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | java.lang.String | Базовый URI связывающих объектов |
| relativeUri | java.lang.String | Относительный URI к связанному объекту. |

**Возвращаемое значение:**
java.lang.String - Абсолютный URI или null, если относительный URI не может быть разрешён.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Отображает URI на объект, содержащий фактический ресурс.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | java.lang.String | Абсолютный URI к объекту. |

**Возвращаемое значение:**
java.io.InputStream - Объект InputStream или null, если ресурс нельзя передать в поток.