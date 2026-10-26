---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar en SVG-bild.
type: docs
url: /sv/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Representerar en SVG-bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Returnerar SVG-innehåll. |
| [getSvgData()](#getSvgData--) | Returnerar SVG-data. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Returnerar återanropsgränssnitt som används för att lösa externa resurser under SVG-dokumentimport. |
| [getBaseUri()](#getBaseUri--) | Returnerar bas-URI för den angivna SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Sparar SVG-bilden som en EMF-fil. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Returnerar SVG-innehåll. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Returnerar SVG-data. Skrivskyddad byte[].

**Returnerar:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Returnerar återanropsgränssnitt som används för att lösa externa resurser under SVG-dokumentimport. Skrivskyddad [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returnerar:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Returnerar bas-URI för den angivna SVG. Används för att lösa relativa länkar. Skrivskyddad String.

**Returnerar:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Sparar SVG-bilden som en EMF-fil.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Skapar den nya SVG-bilden
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Sparar SVG-bilden som en metafil
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Skapar den nya SVG-bilden
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Sparar SVG-bilden som en metafil
>      svgImage.writeAsEmf(byteStream);
>      // Lägger till metafilen i bildsamlingen
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målsström |