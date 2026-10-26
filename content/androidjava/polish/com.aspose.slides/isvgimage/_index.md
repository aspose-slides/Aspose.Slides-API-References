---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje obraz SVG.
type: docs
url: /pl/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Reprezentuje obraz SVG.
## Metody

| Metoda | Opis |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Zwraca zawartość SVG. |
| [getSvgData()](#getSvgData--) | Zwraca dane SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Zwraca interfejs wywołania zwrotnego używany do rozwiązywania zasobów zewnętrznych podczas importu dokumentów SVG. |
| [getBaseUri()](#getBaseUri--) | Zwraca bazowy URI określonego SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Zapisuje obraz SVG jako plik EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```

Zwraca zawartość SVG. Tylko do odczytu String.

**Zwraca:**  
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```

Zwraca dane SVG. Tylko do odczytu byte[].

**Zwraca:**  
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```

Zwraca interfejs wywołania zwrotnego używany do rozwiązywania zasobów zewnętrznych podczas importu dokumentów SVG. Tylko do odczytu [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Zwraca:**  
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```

Zwraca bazowy URI określonego SVG. Używany do rozwiązywania względnych odnośników. Tylko do odczytu String.

**Zwraca:**  
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Zapisuje obraz SVG jako plik EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
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
>      // Dodaje plik metafile do kolekcji obrazów
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |