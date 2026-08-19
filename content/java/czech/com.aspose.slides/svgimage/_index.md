---
title: SvgImage
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje SVG obrázek.
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

Represents an SVG image.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Vytvoří nový objekt SvgImage. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Vytvoří nový objekt SvgImage. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Vytvoří nový objekt SvgImage. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří nový objekt SvgImage. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří nový objekt SvgImage. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Vytvoří nový objekt SvgImage. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getSvgData()](#getSvgData--) | Vrací data SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Vrací rozhraní zpětného volání použité k řešení externích zdrojů během importu dokumentů Svg. |
| [getBaseUri()](#getBaseUri--) | Vrací základní URI specifikovaného Svg. |
| [getSvgContent()](#getSvgContent--) | Vrací obsah SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Uloží obrázek SVG jako soubor EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Svg data. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgContent | java.lang.String | Svg content. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Svg stream. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Svg data. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání použitý k načítání externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| baseUri | java.lang.String | Základní URI specifikovaného Svg. Použito k řešení relativních odkazů. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| svgContent | java.lang.String | Svg content. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání použitý k načítání externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| baseUri | java.lang.String | Základní URI specifikovaného Svg. Použito k řešení relativních odkazů. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Vytvoří nový objekt SvgImage.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Svg stream. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objekt zpětného volání použitý k načítání externích objektů. Pokud je tento parametr null, všechny externí objekty budou ignorovány. |
| baseUri | java.lang.String | Základní URI specifikovaného Svg. Použito k řešení relativních odkazů. |

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

Vrací rozhraní zpětného volání použité k řešení externích zdrojů během importu dokumentů Svg. Pouze pro čtení [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Návratová hodnota:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Vrací základní URI specifikovaného Svg. Použito k řešení relativních odkazů. Pouze pro čtení String.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |