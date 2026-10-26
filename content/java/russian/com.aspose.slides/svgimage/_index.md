---
title: SvgImage
second_title: Справочник API Aspose.Slides для Java
description: Представляет SVG-изображение.
type: docs
url: /ru/com.aspose.slides/svgimage/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Представляет SVG-изображение.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Создаёт новый объект SvgImage. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Создаёт новый объект SvgImage. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Создаёт новый объект SvgImage. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт новый объект SvgImage. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт новый объект SvgImage. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт новый объект SvgImage. |

## Методы

| Метод | Описание |
| --- | --- |
| [getSvgData()](#getSvgData--) | Возвращает данные SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Возвращает интерфейс обратного вызова, используемый для разрешения внешних ресурсов при импорте документов SVG. |
| [getBaseUri()](#getBaseUri--) | Возвращает базовый URI указанного SVG. |
| [getSvgContent()](#getSvgContent--) | Возвращает содержимое SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Сохраняет SVG-изображение в файл EMF. |

### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Создаёт новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Данные SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Создаёт новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgContent | java.lang.String | Содержимое SVG. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Создаёт новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток SVG. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Создаёт новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Данные SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект обратного вызова, используемый для получения внешних объектов. Если параметр равен null, все внешние объекты будут игнорироваться. |
| baseUri | java.lang.String | Базовый URI указанного SVG. Используется для разрешения относительных ссылок. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Создаёт новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgContent | java.lang.String | Содержимое SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект обратного вызова, используемый для получения внешних объектов. Если параметр равен null, все внешние объекты будут игнорироваться. |
| baseUri | java.lang.String | Базовый URI указанного SVG. Используется для разрешения относительных ссылок. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Создаёт новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект обратного вызова, используемый для получения внешних объектов. Если параметр равен null, все внешние объекты будут игнорироваться. |
| baseUri | java.lang.String | Базовый URI указанного SVG. Используется для разрешения относительных ссылок. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Возвращает данные SVG. Только для чтения byte[].

**Возвращаемое значение:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Возвращает интерфейс обратного вызова, используемый для разрешения внешних ресурсов при импорте документов SVG. Только для чтения [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Возвращаемое значение:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Возвращает базовый URI указанного SVG. Используется для разрешения относительных ссылок. Только для чтения String.

**Возвращаемое значение:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Возвращает содержимое SVG. Только для чтения String.

**Возвращаемое значение:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Сохраняет SVG-изображение в файл EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Создаёт новое SVG-изображение
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Сохраняет SVG-изображение как метафайл
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Создаёт новое SVG-изображение
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Сохраняет SVG-изображение как метафайл
>      svgImage.writeAsEmf(byteStream);
>      // Добавляет метафайл в коллекцию изображений
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |
