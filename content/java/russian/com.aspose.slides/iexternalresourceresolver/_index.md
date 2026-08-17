---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to resolve external resources during Html Svg documents import.
type: docs
url: /ru/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Интерфейс обратного вызова, используемый для разрешения внешних ресурсов во время импорта документов Html, Svg.
## Методы

| Метод | Описание |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


Разрешает абсолютный URI из базового и относительного URI.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | java.lang.String | Базовый URI связывающих объектов |
| relativeUri | java.lang.String | Относительный URI к связанному объекту. |

**Возвращаемое значение:**
java.lang.String - Абсолютный URI или null, если относительный URI не может быть разрешен.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```


Отображает URI на объект, содержащий фактический ресурс.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | java.lang.String | Абсолютный URI к объекту. |

**Возвращаемое значение:**
java.io.InputStream - Объект InputStream или null, если ресурс невозможно передать в поток.