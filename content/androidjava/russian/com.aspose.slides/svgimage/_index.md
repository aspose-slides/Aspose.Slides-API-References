---
title: SvgImage
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет изображение SVG.
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

Представляет изображение SVG.
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Создает новый объект SvgImage. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Создает новый объект SvgImage. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Создает новый объект SvgImage. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создает новый объект SvgImage. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создает новый объект SvgImage. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создает новый объект SvgImage. |
## Methods

| Method | Description |
| --- | --- |
| [getSvgData()](#getSvgData--) | Возвращает данные SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Возвращает интерфейс обратного вызова, используемый для разрешения внешних ресурсов во время импорта документов Svg. |
| [getBaseUri()](#getBaseUri--) | Возвращает базовый URI указанного Svg. |
| [getSvgContent()](#getSvgContent--) | Возвращает содержимое SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Сохраняет изображение SVG в файл EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Создает новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Данные Svg. |
### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Создает новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgContent | java.lang.String | Содержимое Svg. |
### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Создает новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток Svg. |
### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Создает новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Данные Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| baseUri | java.lang.String | Базовый URI указанного Svg. Используется для разрешения относительных ссылок. |
### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Создает новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgContent | java.lang.String | Содержимое Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| baseUri | java.lang.String | Базовый URI указанного Svg. Используется для разрешения относительных ссылок. |
### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Создает новый объект SvgImage.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| baseUri | java.lang.String | Базовый URI указанного Svg. Используется для разрешения относительных ссылок. |
### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Возвращает данные SVG. Только для чтения byte[].

**Returns:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Возвращает интерфейс обратного вызова, используемый для разрешения внешних ресурсов во время импорта документов Svg. Только для чтения [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returns:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Возвращает базовый URI указанного Svg. Используется для разрешения относительных ссылок. Только для чтения String.

**Returns:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Возвращает содержимое SVG. Только для чтения String.

**Returns:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Сохраняет изображение SVG в файл EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Creates the new SVG image
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Saves the SVG image as a metafille
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Creates the new SVG image
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Saves the SVG image as a metafille
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |