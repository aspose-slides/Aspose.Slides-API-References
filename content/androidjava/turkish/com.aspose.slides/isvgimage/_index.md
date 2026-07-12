---
title: ISvgImage
second_title: Aspose.Slides for Android Java API Referansı aracılığıyla
description: Bir SVG görüntüsü temsil eder.
type: docs
url: /tr/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Bir SVG görüntüsü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | SVG içeriğini döndürür. |
| [getSvgData()](#getSvgData--) | SVG verisini döndürür. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | SVG belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri arama arayüzünü döndürür. |
| [getBaseUri()](#getBaseUri--) | Belirtilen SVG'nin temel URI'sını döndürür. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | SVG görüntüsünü EMF dosyası olarak kaydeder. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


SVG içeriğini döndürür. Salt okunur String.

**Returns:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


SVG verisini döndürür. Salt okunur byte[].

**Returns:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


SVG belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri arama arayüzünü döndürür. Salt okunur [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returns:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Belirtilen SVG'nin temel URI'sını döndürür. Göreceli bağlantıları çözmek için kullanılır. Salt okunur String.

**Returns:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


SVG görüntüsünü EMF dosyası olarak kaydeder.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Yeni SVG görüntüsü oluşturur
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // SVG görüntüsünü metafile olarak kaydeder
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Yeni SVG görüntüsü oluşturur
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // SVG görüntüsünü metafile olarak kaydeder
>      svgImage.writeAsEmf(byteStream);
>      // Metafile'i görüntü koleksiyonuna ekler
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |