---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an SVG image.
type: docs
url: /nl/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Stelt een SVG-afbeelding voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Retourneert SVG-inhoud. |
| [getSvgData()](#getSvgData--) | Retourneert SVG-gegevens. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Retourneert callback-interface die wordt gebruikt om externe bronnen te resolven tijdens het importeren van SVG-documenten. |
| [getBaseUri()](#getBaseUri--) | Retourneert basis-URI van de opgegeven SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slaat de SVG-afbeelding op als een EMF-bestand. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Retourneert SVG-inhoud. Alleen-lezen String.

**Returns:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Retourneert SVG-gegevens. Alleen-lezen byte[].

**Returns:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Retourneert callback-interface die wordt gebruikt om externe bronnen te resolven tijdens het importeren van SVG-documenten. Alleen-lezen [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returns:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Retourneert basis-URI van de opgegeven SVG. Wordt gebruikt om relatieve links te resolven. Alleen-lezen String.

**Returns:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Slaat de SVG-afbeelding op als een EMF-bestand.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doel-stroom |