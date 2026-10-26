---
title: SvgImage
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una imagen SVG.
type: docs
url: /es/com.aspose.slides/svgimage/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Representa una imagen SVG.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Crea un nuevo objeto SvgImage. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Crea un nuevo objeto SvgImage. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Crea un nuevo objeto SvgImage. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea un nuevo objeto SvgImage. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea un nuevo objeto SvgImage. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Crea un nuevo objeto SvgImage. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSvgData()](#getSvgData--) | Devuelve los datos SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Devuelve la interfaz de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos Svg. |
| [getBaseUri()](#getBaseUri--) | Devuelve el URI base del Svg especificado. |
| [getSvgContent()](#getSvgContent--) | Devuelve el contenido SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Guarda la imagen SVG como un archivo EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Crea un nuevo objeto SvgImage.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Datos SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Crea un nuevo objeto SvgImage.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgContent | java.lang.String | Contenido SVG. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Crea un nuevo objeto SvgImage.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo SVG. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Crea un nuevo objeto SvgImage.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Datos SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null, todos los objetos externos serán ignorados. |
| baseUri | java.lang.String | URI base del Svg especificado. Se usa para resolver enlaces relativos. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Crea un nuevo objeto SvgImage.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgContent | java.lang.String | Contenido SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null, todos los objetos externos serán ignorados. |
| baseUri | java.lang.String | URI base del Svg especificado. Se usa para resolver enlaces relativos. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Crea un nuevo objeto SvgImage.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Un objeto de devolución de llamada usado para obtener objetos externos. Si este parámetro es null, todos los objetos externos serán ignorados. |
| baseUri | java.lang.String | URI base del Svg especificado. Se usa para resolver enlaces relativos. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Devuelve los datos SVG. Solo lectura byte[].

**Devuelve:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Devuelve la interfaz de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos Svg. Solo lectura [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Devuelve:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Devuelve el URI base del Svg especificado. Se usa para resolver enlaces relativos. Solo lectura String.

**Devuelve:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Devuelve el contenido SVG. Solo lectura String.

**Devuelve:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Guarda la imagen SVG como un archivo EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Crea la nueva imagen SVG
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Guarda la imagen SVG como un metafile
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Crea la nueva imagen SVG
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Guarda la imagen SVG como un metafile
>      svgImage.writeAsEmf(byteStream);
>      // Agrega el metafile a la colección de imágenes
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream de destino |