---
title: SvgImage
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje obrázek SVG.
type: docs
url: /cs/com.aspose.slides/svgimage/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Reprezentuje obrázek SVG.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Creates new SvgImage object. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Creates new SvgImage object. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getSvgData()](#getSvgData--) | Returns SVG data. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Return callback interface used to resolve external resources during Svg documents import. |
| [getBaseUri()](#getBaseUri--) | Returns base URI of the specified Svg. |
| [getSvgContent()](#getSvgContent--) | Returns SVG content. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Saves the SVG image as an EMF file. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```


Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Data SVG. |
### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```


Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgContent | java.lang.String | Obsah SVG. |
### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | SVG proud. |
### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```


Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Data SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| baseUri | java.lang.String | Základní URI zadaného Svg. Používá se k řešení relativních odkazů. |
### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```


Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgContent | java.lang.String | Obsah SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| baseUri | java.lang.String | Základní URI zadaného Svg. Používá se k řešení relativních odkazů. |
### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```


Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | SVG proud. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání používaný k načtení externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| baseUri | java.lang.String | Základní URI zadaného Svg. Používá se k řešení relativních odkazů. |
### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```


Vrací data SVG. Pouze pro čtení byte[].

**Návratová hodnota:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```


Vrací rozhraní zpětného volání používané k řešení externích zdrojů během importu dokumentů Svg. Pouze pro čtení [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Návratová hodnota:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```


Vrací základní URI zadaného Svg. Používá se k řešení relativních odkazů. Pouze pro čtení String.

**Návratová hodnota:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```


Vrací obsah SVG. Pouze pro čtení String.

**Návratová hodnota:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```


Uloží obrázek SVG jako soubor EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Vytvoří nový SVG obrázek
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Uloží SVG obrázek jako metafil
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Vytvoří nový SVG obrázek
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Uloží SVG obrázek jako metafil
>      svgImage.writeAsEmf(byteStream);
>      // Přidá metafil do kolekce obrázků
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |