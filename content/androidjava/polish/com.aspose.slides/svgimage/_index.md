---
title: SvgImage
second_title: Aspose.Slides dla Androida za pośrednictwem odniesienia API Java
description: Reprezentuje obraz SVG.
type: docs
url: /pl/com.aspose.slides/svgimage/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Reprezentuje obraz SVG.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Tworzy nowy obiekt SvgImage. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Tworzy nowy obiekt SvgImage. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Tworzy nowy obiekt SvgImage. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy nowy obiekt SvgImage. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy nowy obiekt SvgImage. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Tworzy nowy obiekt SvgImage. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getSvgData()](#getSvgData--) | Zwraca dane SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Zwraca interfejs wywołania zwrotnego używany do rozwiązywania zasobów zewnętrznych podczas importu dokumentów SVG. |
| [getBaseUri()](#getBaseUri--) | Zwraca bazowy URI określonego SVG. |
| [getSvgContent()](#getSvgContent--) | Zwraca zawartość SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Zapisuje obraz SVG jako plik EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

Tworzy nowy obiekt SvgImage.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Dane SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Tworzy nowy obiekt SvgImage.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgContent | java.lang.String | Zawartość SVG. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Tworzy nowy obiekt SvgImage.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień SVG. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Tworzy nowy obiekt SvgImage.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Dane SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli parametr jest równy null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| baseUri | java.lang.String | Bazowy URI określonego SVG. Używany do rozwiązywania odnośników względnych. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Tworzy nowy obiekt SvgImage.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgContent | java.lang.String | Zawartość SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli parametr jest równy null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| baseUri | java.lang.String | Bazowy URI określonego SVG. Używany do rozwiązywania odnośników względnych. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Tworzy nowy obiekt SvgImage.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Obiekt wywołania zwrotnego używany do pobierania obiektów zewnętrznych. Jeśli parametr jest równy null, wszystkie obiekty zewnętrzne zostaną zignorowane. |
| baseUri | java.lang.String | Bazowy URI określonego SVG. Używany do rozwiązywania odnośników względnych. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Zwraca dane SVG. Tylko do odczytu byte[].

**Zwraca:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Zwraca interfejs wywołania zwrotnego używany do rozwiązywania zasobów zewnętrznych podczas importu dokumentów SVG. Tylko do odczytu [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Zwraca:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Zwraca bazowy URI określonego SVG. Używany do rozwiązywania odnośników względnych. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

Zwraca zawartość SVG. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Zapisuje obraz SVG jako plik EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Tworzy nowy obraz SVG
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Zapisuje obraz SVG jako plik metafile
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Tworzy nowy obraz SVG
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Zapisuje obraz SVG jako plik metafile
>      svgImage.writeAsEmf(byteStream);
>      // Dodaje metafile do kolekcji obrazów
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |