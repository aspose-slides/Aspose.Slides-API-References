---
title: SvgImage
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en SVG-bild.
type: docs
url: /sv/com.aspose.slides/svgimage/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Representerar en SVG-bild.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Skapar ett nytt SvgImage-objekt. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Skapar ett nytt SvgImage-objekt. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Skapar ett nytt SvgImage-objekt. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar ett nytt SvgImage-objekt. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar ett nytt SvgImage-objekt. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar ett nytt SvgImage-objekt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSvgData()](#getSvgData--) | Returnerar SVG-data. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Returnerar återuppringningsgränssnitt som används för att lösa externa resurser under import av SVG-dokument. |
| [getBaseUri()](#getBaseUri--) | Returnerar bas-URI för den angivna SVG. |
| [getSvgContent()](#getSvgContent--) | Returnerar SVG-innehåll. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Sparar SVG-bilden som en EMF-fil. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```


Skapar ett nytt SvgImage-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Svg-data. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```


Skapar ett nytt SvgImage-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgContent | java.lang.String | Svg-innehåll. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Skapar ett nytt SvgImage-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Svg-ström. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```


Skapar ett nytt SvgImage-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Svg-data. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| baseUri | java.lang.String | Bas-URI för den angivna SVG. Används för att lösa relativa länkar. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```


Skapar ett nytt SvgImage-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgContent | java.lang.String | Svg-innehåll. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| baseUri | java.lang.String | Bas-URI för den angivna SVG. Används för att lösa relativa länkar. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```


Skapar ett nytt SvgImage-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Svg-ström. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| baseUri | java.lang.String | Bas-URI för den angivna SVG. Används för att lösa relativa länkar. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```


Returnerar SVG-data. Skrivskyddad byte[].

**Returnerar:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```


Returnerar återuppringningsgränssnitt som används för att lösa externa resurser under import av SVG-dokument. Skrivskyddad [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returnerar:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```


Returnerar bas-URI för den angivna SVG. Används för att lösa relativa länkar. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```


Returnerar SVG-innehåll. Skrivskyddad String.

**Returnerar:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```


Sparar SVG-bilden som en EMF-fil.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målsström |