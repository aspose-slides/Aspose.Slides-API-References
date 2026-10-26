---
title: IExternalResourceResolver
second_title: Aspose.Slides для Android через Java API Reference
description: Интерактивный интерфейс, используемый для разрешения внешних ресурсов при импорте документов Html и Svg.
type: docs
url: /ru/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Интерактивный интерфейс, используемый для разрешения внешних ресурсов при импорте документов Html, Svg.
## Методы

| Метод | Описание |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Разрешает абсолютный URI из базового и относительного URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Отображает URI на объект, содержащий фактический ресурс. |
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
java.lang.String — абсолютный URI или null, если относительный URI не может быть разрешён.
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
java.io.InputStream — объект InputStream или null, если ресурс невозможно передать в поток.