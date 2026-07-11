---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет SVG-изображение.
type: docs
url: /ru/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Представляет SVG-изображение.
## Методы

| Метод | Описание |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Возвращает содержимое SVG. |
| [getSvgData()](#getSvgData--) | Возвращает данные SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Возвращает интерфейс обратного вызова, используемый для разрешения внешних ресурсов при импорте SVG-документов. |
| [getBaseUri()](#getBaseUri--) | Возвращает базовый URI указанного SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Сохраняет SVG-изображение в файл EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Возвращает содержимое SVG. Только для чтения String.

**Возвращает:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Возвращает данные SVG. Только для чтения byte[].

**Возвращает:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Возвращает интерфейс обратного вызова, используемый для разрешения внешних ресурсов при импорте SVG-документов. Только для чтения [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Возвращает:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Возвращает базовый URI указанного SVG. Используется для разрешения относительных ссылок. Только для чтения String.

**Возвращает:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Сохраняет SVG-изображение в файл EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
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
>      // Saves the SVG image as a metafile
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