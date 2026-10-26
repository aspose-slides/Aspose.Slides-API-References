---
title: SvgImage
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein SVG-Bild dar.
type: docs
url: /de/com.aspose.slides/svgimage/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Stellt ein SVG-Bild dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Erstellt ein neues SvgImage-Objekt. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Erstellt ein neues SvgImage-Objekt. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Erstellt ein neues SvgImage-Objekt. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Erstellt ein neues SvgImage-Objekt. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Erstellt ein neues SvgImage-Objekt. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Erstellt ein neues SvgImage-Objekt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSvgData()](#getSvgData--) | Gibt SVG-Daten zurück. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Gibt das Rückrufinterface zurück, das zum Auflösen externer Ressourcen während des Imports von Svg-Dokumenten verwendet wird. |
| [getBaseUri()](#getBaseUri--) | Gibt die Basis-URI des angegebenen Svg zurück. |
| [getSvgContent()](#getSvgContent--) | Gibt den SVG-Inhalt zurück. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Speichert das SVG-Bild als EMF-Datei. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Erstellt ein neues SvgImage-Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Svg-Daten. |
### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Erstellt ein neues SvgImage-Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgContent | java.lang.String | Svg-Inhalt. |
### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Erstellt ein neues SvgImage-Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Svg-Stream. |
### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Erstellt ein neues SvgImage-Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Svg-Daten. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ein Rückrufobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| baseUri | java.lang.String | Basis-URI des angegebenen Svg. Wird verwendet, um relative Links aufzulösen. |
### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Erstellt ein neues SvgImage-Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgContent | java.lang.String | Svg-Inhalt. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ein Rückrufobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| baseUri | java.lang.String | Basis-URI des angegebenen Svg. Wird verwendet, um relative Links aufzulösen. |
### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Erstellt ein neues SvgImage-Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Svg-Stream. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ein Rückrufobjekt, das zum Abrufen externer Objekte verwendet wird. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| baseUri | java.lang.String | Basis-URI des angegebenen Svg. Wird verwendet, um relative Links aufzulösen. |
### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Gibt SVG-Daten zurück. Nur lesbar byte[].

**Rückgabe:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Gibt das Rückrufinterface zurück, das zum Auflösen externer Ressourcen während des Imports von Svg-Dokumenten verwendet wird. Nur lesbar [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Rückgabe:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Gibt die Basis-URI des angegebenen Svg zurück. Wird verwendet, um relative Links aufzulösen. Nur lesbar String.

**Rückgabe:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Gibt den SVG-Inhalt zurück. Nur lesbar String.

**Rückgabe:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Speichert das SVG-Bild als EMF-Datei.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |