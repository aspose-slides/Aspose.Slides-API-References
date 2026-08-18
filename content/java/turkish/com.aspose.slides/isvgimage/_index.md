---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: Bir SVG görüntüsünü temsil eder.
type: docs
url: /tr/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Bir SVG görüntüsünü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | SVG içeriğini döndürür. |
| [getSvgData()](#getSvgData--) | SVG verisini döndürür. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | SVG belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri çağırma arayüzünü döndürür. |
| [getBaseUri()](#getBaseUri--) | Belirtilen SVG'nin temel URI'sını döndürür. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | SVG görüntüsünü EMF dosyası olarak kaydeder. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```

SVG içeriğini döndürür. Salt-okunur String.

**Returns:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```

SVG verisini döndürür. Salt-okunur byte[].

**Returns:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```

SVG belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri çağırma arayüzünü döndürür. Salt-okunur [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Returns:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```

Belirtilen SVG'nin temel URI'sını döndürür. Göreli bağlantıları çözmek için kullanılır. Salt-okunur String.

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
>  // Yeni SVG görüntüsünü oluşturur
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // SVG görüntüsünü bir metafile olarak kaydeder
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Yeni SVG görüntüsünü oluşturur
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // SVG görüntüsünü bir metafile olarak kaydeder
>      svgImage.writeAsEmf(byteStream);
>      // Metafile'yi görüntü koleksiyonuna ekler
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |