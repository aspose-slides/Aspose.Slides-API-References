---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Egy SVG képet képvisel.
type: docs
url: /hu/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Egy SVG képet képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Visszaadja az SVG tartalmat. |
| [getSvgData()](#getSvgData--) | Visszaadja az SVG adatokat. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Visszaadja a visszahívási interfészt, amely az SVG dokumentumok importálása során külső erőforrások feloldására szolgál. |
| [getBaseUri()](#getBaseUri--) | Visszaadja a megadott SVG alap-URI-jét. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Elmenti az SVG képet EMF fájlként. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Visszaadja az SVG tartalmat. Csak-olvasó String.

**Returns:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Visszaadja az SVG adatokat. Csak-olvasó byte[].

**Returns:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Visszaadja a visszahívási interfészt, amely az SVG dokumentumok importálása során külső erőforrások feloldására szolgál. Csak-olvasó [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returns:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Visszaadja a megadott SVG alap-URI-jét. Relatív hivatkozások feloldására használható. Csak-olvasó String.

**Returns:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Elmenti az SVG képet EMF fájlként.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |