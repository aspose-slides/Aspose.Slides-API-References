---
title: SvgImage
second_title: Aspose.Slides Androidra a Java API hivatkozásán keresztül
description: SVG képet ábrázol.
type: docs
url: /hu/com.aspose.slides/svgimage/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

SVG képet képvisel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Új SvgImage objektumot hoz létre. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Új SvgImage objektumot hoz létre. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Új SvgImage objektumot hoz létre. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Új SvgImage objektumot hoz létre. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Új SvgImage objektumot hoz létre. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Új SvgImage objektumot hoz létre. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSvgData()](#getSvgData--) | Visszaadja az SVG adatot. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Visszatér a hívási felületre, amely a külső erőforrások feloldására szolgál SVG dokumentumok importálása során. |
| [getBaseUri()](#getBaseUri--) | Visszaadja a megadott SVG alap-URI-ját. |
| [getSvgContent()](#getSvgContent--) | Visszaadja az SVG tartalmat. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Elmenti az SVG képet EMF fájlként. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Új SvgImage objektumot hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Svg adat. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Új SvgImage objektumot hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgContent | java.lang.String | Svg tartalom. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Új SvgImage objektumot hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Svg adatfolyam. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Új SvgImage objektumot hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | byte[] | Svg adat. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Egy visszahívási objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül lesz hagyva. |
| baseUri | java.lang.String | A megadott SVG alap-URI-ja. Relatív hivatkozások feloldásához használatos. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Új SvgImage objektumot hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| svgContent | java.lang.String | Svg tartalom. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Egy visszahívási objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül lesz hagyva. |
| baseUri | java.lang.String | A megadott SVG alap-URI-ja. Relatív hivatkozások feloldásához használatos. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Új SvgImage objektumot hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Svg adatfolyam. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Egy visszahívási objektum, amely a külső objektumok lekérésére szolgál. Ha ez a paraméter null, akkor minden külső objektum figyelmen kívül lesz hagyva. |
| baseUri | java.lang.String | A megadott SVG alap-URI-ja. Relatív hivatkozások feloldásához használatos. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Visszaadja az SVG adatot. Csak olvasható byte[].

**Visszatér:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Visszatér a hívási felületre, amely a külső erőforrások feloldására szolgál SVG dokumentumok importálása során. Csak olvasható [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Visszatér:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Visszaadja a megadott SVG alap-URI-ját. Relatív hivatkozások feloldásához használatos. Csak olvasható String.

**Visszatér:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Visszaadja az SVG tartalmat. Csak olvasható String.

**Visszatér:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Elmenti az SVG képet EMF fájlként.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Létrehozza az új SVG képet
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Elmenti az SVG képet metafájlként
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Létrehozza az új SVG képet
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Elmenti az SVG képet metafájlként
>      svgImage.writeAsEmf(byteStream);
>      // Hozzáadja a metafájlt a képgyűjteményhez
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél adatfolyam |