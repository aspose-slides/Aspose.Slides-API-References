---
title: Output
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolekcję elementów wyjściowych dla IWebDocument.
type: docs
url: /pl/com.aspose.slides/output/
---
**Dziedziczenie:**
java.lang.Object
```
public final class Output
```

Reprezentuje kolekcję elementów wyjściowych dla IWebDocument.
## Metody

| Metoda | Opis |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Dodaje element wyjściowy dla obiektu kontekstu. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Dodaje element wyjściowy dla obrazu. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Dodaje element wyjściowy dla obrazu. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Dodaje element wyjściowy dla wideo. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Dodaje element wyjściowy dla dźwięku. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Tworzy i dodaje element pliku wyjściowego dla określonej czcionki. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Dodaje element wyjściowy dla treści tekstowej. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Wiąże zasób z plikiem wyjściowym. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Zwraca ścieżkę dla podanego zasobu. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Dodaje element wyjściowy dla obiektu kontekstu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka wyjściowa. |
| templateKey | java.lang.String | Klucz szablonu używanego do przekształcenia obiektu kontekstu przed wyjściem. |
| contextObject | TContextObject | Obiekt kontekstu. |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) obiekt dla obiektu kontekstu.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Dodaje element wyjściowy dla obrazu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka wyjściowa. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obraz do wyjścia. |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) obiekt dla obrazu.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Dodaje element wyjściowy dla obrazu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka wyjściowa. |
| image | [IImage](../../com.aspose.slides/iimage) | Obraz do wyjścia. |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) obiekt dla obrazu.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Dodaje element wyjściowy dla wideo.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka wyjściowa. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Wideo do wyjścia. |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) obiekt dla wideo.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```


Dodaje element wyjściowy dla audio.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka wyjściowa. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio do wyjścia. |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) obiekt dla audio.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Tworzy i dodaje element pliku wyjściowego dla określonej czcionki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka pliku, w której zostanie zapisany wyjściowy font. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Dane czcionki, które mają zostać zapisane w wyjściu. |
| fontStyle | int | Styl czcionki (np. Regular, Bold, Italic). |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Instancja [IOutputFile](../../com.aspose.slides/ioutputfile) dla wygenerowanej czcionki.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Dodaje element wyjściowy dla treści tekstowej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka wyjściowa. |
| textContent | java.lang.String | Treść do wyjścia. |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) obiekt dla treści tekstowej.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Wiąże zasób z plikiem wyjściowym.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Plik wyjściowy. |
| obj | java.lang.Object | Obiekt zasobu. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Zwraca ścieżkę dla podanego zasobu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt zasobu. |

**Zwraca:**
java.lang.String - Ścieżka zasobu.