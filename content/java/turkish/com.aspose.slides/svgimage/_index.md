---
title: SvgImage
second_title: Aspose.Slides for Java API Referansı
description: Bir SVG görüntüsünü temsil eder.
type: docs
url: /tr/com.aspose.slides/svgimage/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Bir SVG görüntüsünü temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Yeni SvgImage nesnesi oluşturur. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Yeni SvgImage nesnesi oluşturur. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Yeni SvgImage nesnesi oluşturur. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Yeni SvgImage nesnesi oluşturur. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Yeni SvgImage nesnesi oluşturur. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Yeni SvgImage nesnesi oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSvgData()](#getSvgData--) | SVG verilerini döndürür. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Svg belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri dönüş arayüzünü döndürür. |
| [getBaseUri()](#getBaseUri--) | Belirtilen Svg'nin temel URI'sını döndürür. |
| [getSvgContent()](#getSvgContent--) | SVG içeriğini döndürür. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | SVG görüntüsünü EMF dosyası olarak kaydeder. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Yeni SvgImage nesnesi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| data | byte[] | Svg verisi. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Yeni SvgImage nesnesi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| svgContent | java.lang.String | Svg içeriği. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Yeni SvgImage nesnesi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Svg akışı. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Yeni SvgImage nesnesi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| data | byte[] | Svg verisi. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri dönüş nesnesi. Bu parametre null ise tüm harici nesneler yok sayılır. |
| baseUri | java.lang.String | Belirtilen Svg'nin temel URI'sı. Göreceli bağlantıları çözmek için kullanılır. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Yeni SvgImage nesnesi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| svgContent | java.lang.String | Svg içeriği. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri dönüş nesnesi. Bu parametre null ise tüm harici nesneler yok sayılır. |
| baseUri | java.lang.String | Belirtilen Svg'nin temel URI'sı. Göreceli bağlantıları çözmek için kullanılır. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Yeni SvgImage nesnesi oluşturur.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Svg akışı. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri dönüş nesnesi. Bu parametre null ise tüm harici nesneler yok sayılır. |
| baseUri | java.lang.String | Belirtilen Svg'nin temel URI'sı. Göreceli bağlantıları çözmek için kullanılır. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

SVG verilerini döndürür. Salt okunur byte[].

**Döndürür:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Svg belgeleri içe aktarılırken harici kaynakları çözmek için kullanılan geri dönüş arayüzünü döndürür. Salt okunur [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Döndürür:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Belirtilen Svg'nin temel URI'sını döndürür. Göreceli bağlantıları çözmek için kullanılır. Salt okunur String.

**Döndürür:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

SVG içeriğini döndürür. Salt okunur String.

**Döndürür:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

SVG görüntüsünü EMF dosyası olarak kaydeder.

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

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |