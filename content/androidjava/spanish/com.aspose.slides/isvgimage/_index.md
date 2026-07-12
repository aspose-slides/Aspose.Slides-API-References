---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Representa una imagen SVG.
type: docs
url: /es/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Representa una imagen SVG.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Devuelve el contenido SVG. |
| [getSvgData()](#getSvgData--) | Devuelve los datos SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Devuelve la interfaz de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos SVG. |
| [getBaseUri()](#getBaseUri--) | Devuelve el URI base del SVG especificado. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Guarda la imagen SVG como un archivo EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Devuelve el contenido SVG. String de solo lectura.

**Devuelve:**  
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Devuelve los datos SVG. byte[] de solo lectura.

**Devuelve:**  
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Devuelve la interfaz de devolución de llamada utilizada para resolver recursos externos durante la importación de documentos SVG. [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) de solo lectura.

**Devuelve:**  
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Devuelve el URI base del SVG especificado. Utilizado para resolver enlaces relativos. String de solo lectura.

**Devuelve:**  
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Guarda la imagen SVG como un archivo EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
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
>      // Añade el metafile a la colección de imágenes
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |