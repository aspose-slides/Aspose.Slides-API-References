---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: Represents an SVG image.
type: docs
url: /ru/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Представляет SVG-изображение.
## Методы

| Метод | Описание |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Возвращает SVG-контент. |
| [getSvgData()](#getSvgData--) | Возвращает SVG-данные. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Возвращает интерфейс обратного вызова, используемый для разрешения внешних ресурсов при импорте SVG-документов. |
| [getBaseUri()](#getBaseUri--) | Возвращает базовый URI указанного SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Сохраняет SVG-изображение в файл EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```

Возвращает SVG-контент. Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```

Возвращает SVG-данные. Только для чтения byte[].

**Возвращаемое значение:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```

Возвращает интерфейс обратного вызова, используемый для разрешения внешних ресурсов при импорте SVG-документов. Только для чтения [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Возвращаемое значение:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```

Возвращает базовый URI указанного SVG. Используется для разрешения относительных ссылок. Только для чтения String.

**Возвращаемое значение:**
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
>  // Создает новое SVG-изображение
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Сохраняет SVG-изображение как метафайл
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Создает новое SVG-изображение
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