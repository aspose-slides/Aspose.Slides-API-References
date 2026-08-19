---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: Představuje SVG obrázek.
type: docs
url: /cs/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Představuje SVG obrázek.
## Metody

| Metoda | Popis |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Returns SVG content. |
| [getSvgData()](#getSvgData--) | Returns SVG data. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Return callback interface used to resolve external resources during SVG documents import. |
| [getBaseUri()](#getBaseUri--) | Returns base URI of the specified SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Saves the SVG image as an EMF file. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Vrací obsah SVG. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Vrací data SVG. Pouze pro čtení byte[].

**Vrací:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Vrací rozhraní zpětného volání použité k rozřešení externích zdrojů během importu SVG dokumentů. Pouze pro čtení [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Vrací:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Vrací základní URI zadaného SVG. Používá se k rozřešení relativních odkazů. Pouze pro čtení String.

**Vrací:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Uloží SVG obrázek jako soubor EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Vytváří nový SVG obrázek
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Ukládá SVG obrázek jako metafile
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Vytváří nový SVG obrázek
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Ukládá SVG obrázek jako metafile
>      svgImage.writeAsEmf(byteStream);
>      // Přidává metafile do kolekce obrázků
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |