---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: Rappresenta un'immagine SVG.
type: docs
url: /it/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Rappresenta un'immagine SVG.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Restituisce il contenuto SVG. |
| [getSvgData()](#getSvgData--) | Restituisce i dati SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Interfaccia di callback utilizzata per risolvere risorse esterne durante l'importazione di documenti SVG. |
| [getBaseUri()](#getBaseUri--) | Restituisce l'URI di base dell'SVG specificato. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Salva l'immagine SVG come file EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Restituisce il contenuto SVG. Solo lettura String.

**Restituisce:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Restituisce i dati SVG. Solo lettura byte[].

**Restituisce:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Interfaccia di callback utilizzata per risolvere risorse esterne durante l'importazione di documenti SVG. Solo lettura [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Restituisce:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Restituisce l'URI di base dell'SVG specificato. Utilizzato per risolvere i collegamenti relativi. Solo lettura String.

**Restituisce:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Salva l'immagine SVG come file EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Crea la nuova immagine SVG
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Salva l'immagine SVG come metafille
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
>      // Aggiunge il metafile alla collezione di immagini
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |