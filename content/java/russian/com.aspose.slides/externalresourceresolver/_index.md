---
title: ExternalResourceResolver
second_title: Справочник API Aspose.Slides для Java
description: Класс-обратный вызов, используемый для разрешения внешних ресурсов при импорте документов Html и Svg.
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

Класс-обратный вызов, используемый для разрешения внешних ресурсов при импорте документов Html, Svg.

--------------------

Использование этого резольвера может создать уязвимость, когда предоставленный клиентом HTML или SVG файл заставит серверное программное обеспечение получать локальный или сетевой файл. Используйте с осторожностью. Рекомендуется не указывать ExternalResourceResolver вовсе (будут читаться только встроенные объекты) или создать подкласс, который проверяет корректность указанного uri.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Разрешает абсолютный URI из базового и относительного URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Отображает URI в объект, содержащий фактический ресурс. |

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

Отображает URI в объект, содержащий фактический ресурс.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| absoluteUri | java.lang.String | Абсолютный URI к объекту. |

**Возвращаемое значение:**
java.io.InputStream - Объект InputStream или null, если ресурс нельзя вывести в поток.