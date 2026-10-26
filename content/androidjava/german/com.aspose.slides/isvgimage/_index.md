---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt ein SVG-Bild dar.
type: docs
url: /de/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Stellt ein SVG-Bild dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Gibt den SVG-Inhalt zurück. |
| [getSvgData()](#getSvgData--) | Gibt die SVG-Daten zurück. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Gibt die Callback-Schnittstelle zurück, die zum Auflösen externer Ressourcen beim Import von SVG-Dokumenten verwendet wird. |
| [getBaseUri()](#getBaseUri--) | Gibt die Basis-URI des angegebenen SVG zurück. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Speichert das SVG-Bild als EMF-Datei. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Gibt den SVG-Inhalt zurück. Nur lesbare String.

**Rückgabe:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Gibt die SVG-Daten zurück. Nur lesbare byte[].

**Rückgabe:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Gibt die Callback-Schnittstelle zurück, die zum Auflösen externer Ressourcen beim Import von SVG-Dokumenten verwendet wird. Nur lesbare [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Rückgabe:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Gibt die Basis-URI des angegebenen SVG zurück. Wird zum Auflösen relativer Links verwendet. Nur lesbare String.

**Rückgabe:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Speichert das SVG-Bild als EMF-Datei.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Erstellt das neue SVG-Bild
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Speichert das SVG-Bild als Metadatei
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Erstellt das neue SVG-Bild
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Speichert das SVG-Bild als Metadatei
>      svgImage.writeAsEmf(byteStream);
>      // Fügt die Metadatei zur Bildsammlung hinzu
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |