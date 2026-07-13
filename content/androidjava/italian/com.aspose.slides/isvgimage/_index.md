---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an SVG image.
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
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Restituisce l'interfaccia di callback usata per risolvere le risorse esterne durante l'importazione di documenti SVG. |
| [getBaseUri()](#getBaseUri--) | Restituisce l'URI di base dello SVG specificato. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Salva l'immagine SVG come file EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```

Restituisce il contenuto SVG. String sola lettura.

**Restituisce:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```

Restituisce i dati SVG. byte[] sola lettura.

**Restituisce:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```

Restituisce l'interfaccia di callback usata per risolvere le risorse esterne durante l'importazione di documenti SVG. [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) sola lettura.

**Restituisce:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```

Restituisce l'URI di base dello SVG specificato. Usato per risolvere collegamenti relativi. String sola lettura.

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
| stream | java.io.OutputStream | stream di destinazione |