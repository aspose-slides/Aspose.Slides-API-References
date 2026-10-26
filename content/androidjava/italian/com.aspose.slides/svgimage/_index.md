---
title: SvgImage
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un'immagine SVG.
type: docs
url: /it/com.aspose.slides/svgimage/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Rappresenta un'immagine SVG.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Crea un nuovo oggetto SvgImage. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Crea un nuovo oggetto SvgImage. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Crea un nuovo oggetto SvgImage. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea un nuovo oggetto SvgImage. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea un nuovo oggetto SvgImage. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea un nuovo oggetto SvgImage. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSvgData()](#getSvgData--) | Restituisce i dati SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Restituisce l'interfaccia di callback usata per risolvere risorse esterne durante l'importazione di documenti Svg. |
| [getBaseUri()](#getBaseUri--) | Restituisce l'URI di base dello Svg specificato. |
| [getSvgContent()](#getSvgContent--) | Restituisce il contenuto SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Salva l'immagine SVG come file EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Crea un nuovo oggetto SvgImage.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | Dati SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Crea un nuovo oggetto SvgImage.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgContent | java.lang.String | Contenuto SVG. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Crea un nuovo oggetto SvgImage.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream SVG. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Crea un nuovo oggetto SvgImage.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | Dati SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| baseUri | java.lang.String | URI di base dello Svg specificato. Usato per risolvere collegamenti relativi. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Crea un nuovo oggetto SvgImage.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgContent | java.lang.String | Contenuto SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| baseUri | java.lang.String | URI di base dello Svg specificato. Usato per risolvere collegamenti relativi. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Crea un nuovo oggetto SvgImage.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un oggetto di callback usato per recuperare oggetti esterni. Se questo parametro è null tutti gli oggetti esterni saranno ignorati. |
| baseUri | java.lang.String | URI di base dello Svg specificato. Usato per risolvere collegamenti relativi. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Restituisce i dati SVG. Solo lettura byte[].

**Restituisce:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Restituisce l'interfaccia di callback usata per risolvere risorse esterne durante l'importazione di documenti Svg. Solo lettura [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Restituisce:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Restituisce l'URI di base dello Svg specificato. Usato per risolvere collegamenti relativi. Solo lettura String.

**Restituisce:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Restituisce il contenuto SVG. Solo lettura String.

**Restituisce:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Salva l'immagine SVG come file EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Crea la nuova immagine SVG
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Salva l'immagine SVG come metafile
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Crea la nuova immagine SVG
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Salva l'immagine SVG come metafile
>      svgImage.writeAsEmf(byteStream);
>      // Aggiunge il metafile alla raccolta di immagini
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |