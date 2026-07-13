---
title: Output
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
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
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Dodaje element wyjściowy dla obiektu kontekstowego. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Dodaje element wyjściowy dla obrazu. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Dodaje element wyjściowy dla obrazu. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Dodaje element wyjściowy dla wideo. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Tworzy i dodaje element pliku wyjściowego dla określonej czcionki. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Dodaje element wyjściowy dla treści tekstowej. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Łączy zasób z plikiem wyjściowym. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Zwraca ścieżkę dla podanego zasobu. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Dodaje element wyjściowy dla obiektu kontekstowego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka wyjścia. |
| templateKey | java.lang.String | Klucz szablonu używanego do przekształcenia obiektu kontekstowego przed wyjściem. |
| contextObject | TContextObject | Obiekt kontekstowy. |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) obiekt dla obiektu kontekstowego.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Dodaje element wyjściowy dla obrazu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka wyjścia. |
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
| path | java.lang.String | Ścieżka wyjścia. |
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
| path | java.lang.String | Ścieżka wyjścia. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Wideo do wyjścia. |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) obiekt dla wideo.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Tworzy i dodaje element pliku wyjściowego dla określonej czcionki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka pliku, w którym zostanie zapisane wyjście czcionki. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Dane czcionki do zapisania w wyjściu. |
| fontStyle | int | Styl czcionki (np. Regular, Bold, Italic). |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - An [IOutputFile](../../com.aspose.slides/ioutputfile) instance for the generated font.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Dodaje element wyjściowy dla treści tekstowej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| path | java.lang.String | Ścieżka wyjścia. |
| textContent | java.lang.String | Zawartość do wyjścia. |

**Zwraca:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) obiekt dla treści tekstowej.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Łączy zasób z plikiem wyjściowym.

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