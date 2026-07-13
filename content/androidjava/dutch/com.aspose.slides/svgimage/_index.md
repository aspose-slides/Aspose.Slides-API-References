---
title: SvgImage
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een SVG-afbeelding voor.
type: docs
url: /nl/com.aspose.slides/svgimage/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Stelt een SVG-afbeelding voor.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Maakt een nieuw SvgImage-object aan. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Maakt een nieuw SvgImage-object aan. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Maakt een nieuw SvgImage-object aan. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt een nieuw SvgImage-object aan. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt een nieuw SvgImage-object aan. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt een nieuw SvgImage-object aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSvgData()](#getSvgData--) | Retourneert SVG-gegevens. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Retourneert callback-interface die wordt gebruikt om externe bronnen tijdens het importeren van Svg-documenten op te lossen. |
| [getBaseUri()](#getBaseUri--) | Retourneert de basis-URI van de gespecificeerde Svg. |
| [getSvgContent()](#getSvgContent--) | Retourneert SVG-inhoud. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slaat de SVG-afbeelding op als een EMF-bestand. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Maakt een nieuw SvgImage-object aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Svg-gegevens. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Maakt een nieuw SvgImage-object aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgContent | java.lang.String | Svg-inhoud. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Maakt een nieuw SvgImage-object aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Svg-stream. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Maakt een nieuw SvgImage-object aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Svg-gegevens. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| baseUri | java.lang.String | Basis-URI van de gespecificeerde Svg. Wordt gebruikt om relatieve koppelingen op te lossen. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Maakt een nieuw SvgImage-object aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgContent | java.lang.String | Svg-inhoud. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| baseUri | java.lang.String | Basis-URI van de gespecificeerde Svg. Wordt gebruikt om relatieve koppelingen op te lossen. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Maakt een nieuw SvgImage-object aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Svg-stream. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| baseUri | java.lang.String | Basis-URI van de gespecificeerde Svg. Wordt gebruikt om relatieve koppelingen op te lossen. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Retourneert SVG-gegevens. Alleen-lezen byte[].

**Retourneert:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Retourneert callback-interface die wordt gebruikt om externe bronnen tijdens het importeren van Svg-documenten op te lossen. Alleen-lezen [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Retourneert:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Retourneert de basis-URI van de gespecificeerde Svg. Wordt gebruikt om relatieve koppelingen op te lossen. Alleen-lezen String.

**Retourneert:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Retourneert SVG-inhoud. Alleen-lezen String.

**Retourneert:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Slaat de SVG-afbeelding op als een EMF-bestand.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doel-stream |