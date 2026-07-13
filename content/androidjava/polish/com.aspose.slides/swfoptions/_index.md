---
title: SwfOptions
second_title: Aspose.Slides dla Androida za pośrednictwem odniesienia do API Java
description: Udostępnia opcje, które kontrolują sposób zapisywania prezentacji w formacie Swf.
type: docs
url: /pl/com.aspose.slides/swfoptions/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Udostępnia opcje kontrolujące, jak prezentacja jest zapisywana w formacie Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Utwórz obiekt Presentation, który reprezentuje plik prezentacji
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Zapisywanie prezentacji i stron notatek
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Domyślny konstruktor. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. |
| [getCompressed()](#getCompressed--) | Określa, czy wygenerowany dokument SWF ma być skompresowany, czy nie. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Określa, czy wygenerowany dokument SWF ma być skompresowany, czy nie. |
| [getViewerIncluded()](#getViewerIncluded--) | Określa, czy wygenerowany dokument SWF ma zawierać zintegrowany podgląd dokumentu, czy nie. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Określa, czy wygenerowany dokument SWF ma zawierać zintegrowany podgląd dokumentu, czy nie. |
| [getShowPageBorder()](#getShowPageBorder--) | Określa, czy obramowanie wokół stron ma być wyświetlane. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Określa, czy obramowanie wokół stron ma być wyświetlane. |
| [getShowFullScreen()](#getShowFullScreen--) | Pokaż/ukryj przycisk pełnego ekranu. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Pokaż/ukryj przycisk pełnego ekranu. |
| [getShowPageStepper()](#getShowPageStepper--) | Pokaż/ukryj przełącznik stron. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Pokaż/ukryj przełącznik stron. |
| [getShowSearch()](#getShowSearch--) | Pokaż/ukryj sekcję wyszukiwania. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Pokaż/ukryj sekcję wyszukiwania. |
| [getShowTopPane()](#getShowTopPane--) | Pokaż/ukryj cały górny panel. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Pokaż/ukryj cały górny panel. |
| [getShowBottomPane()](#getShowBottomPane--) | Pokaż/ukryj dolny panel. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Pokaż/ukryj dolny panel. |
| [getShowLeftPane()](#getShowLeftPane--) | Pokaż/ukryj lewy panel. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Pokaż/ukryj lewy panel. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Rozpocznij z otwartym lewym panelem. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Rozpocznij z otwartym lewym panelem. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Włącz/wyłącz menu kontekstowe. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Włącz/wyłącz menu kontekstowe. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Obraz, który będzie wyświetlany jako logo w prawym górnym rogu przeglądarki. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Obraz, który będzie wyświetlany jako logo w prawym górnym rogu przeglądarki. |
| [getLogoLink()](#getLogoLink--) | Pobiera lub ustawia pełny adres hiperłącza dla logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Pobiera lub ustawia pełny adres hiperłącza dla logo. |
| [getJpegQuality()](#getJpegQuality--) | Określa jakość obrazów JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Określa jakość obrazów JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


Domyślny konstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. Domyślnie false.

**Zwraca:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Określa, czy wygenerowany dokument ma zawierać ukryte slajdy, czy nie. Domyślnie false.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


Określa, czy wygenerowany dokument SWF ma być skompresowany, czy nie. Domyślnie true.

**Zwraca:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


Określa, czy wygenerowany dokument SWF ma być skompresowany, czy nie. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


Określa, czy wygenerowany dokument SWF ma zawierać zintegrowany podgląd dokumentu, czy nie. Domyślnie true.

**Zwraca:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


Określa, czy wygenerowany dokument SWF ma zawierać zintegrowany podgląd dokumentu, czy nie. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


Określa, czy obramowanie wokół stron ma być wyświetlane. Domyślnie true.

**Zwraca:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


Określa, czy obramowanie wokół stron ma być wyświetlane. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


Pokaż/ukryj przycisk pełnego ekranu. Może być nadpisane w flashvars. Domyślnie true.

**Zwraca:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


Pokaż/ukryj przycisk pełnego ekranu. Może być nadpisane w flashvars. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


Pokaż/ukryj przełącznik stron. Może być nadpisane w flashvars. Domyślnie true.

**Zwraca:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


Pokaż/ukryj przełącznik stron. Może być nadpisane w flashvars. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


Pokaż/ukryj sekcję wyszukiwania. Może być nadpisane w flashvars. Domyślnie true.

**Zwraca:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


Pokaż/ukryj sekcję wyszukiwania. Może być nadpisane w flashvars. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


Pokaż/ukryj cały górny panel. Może być nadpisane w flashvars. Domyślnie true.

**Zwraca:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


Pokaż/ukryj cały górny panel. Może być nadpisane w flashvars. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


Pokaż/ukryj dolny panel. Może być nadpisane w flashvars. Domyślnie true.

**Zwraca:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


Pokaż/ukryj dolny panel. Może być nadpisane w flashvars. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


Pokaż/ukryj lewy panel. Może być nadpisane w flashvars. Domyślnie true.

**Zwraca:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


Pokaż/ukryj lewy panel. Może być nadpisane w flashvars. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


Rozpocznij z otwartym lewym panelem. Może być nadpisane w flashvars. Domyślnie false.

**Zwraca:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


Rozpocznij z otwartym lewym panelem. Może być nadpisane w flashvars. Domyślnie false.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


Włącz/wyłącz menu kontekstowe. Domyślnie true.

**Zwraca:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


Włącz/wyłącz menu kontekstowe. Domyślnie true.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


Obraz, który będzie wyświetlany jako logo w prawym górnym rogu przeglądarki. Obraz powinien mieć 32x64 piksele i być w formacie PNG, w przeciwnym razie logo może być wyświetlane nieprawidłowo.

**Zwraca:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


Obraz, który będzie wyświetlany jako logo w prawym górnym rogu przeglądarki. Obraz powinien mieć 32x64 piksele i być w formacie PNG, w przeciwnym razie logo może być wyświetlane nieprawidłowo.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


Pobiera lub ustawia pełny adres hiperłącza dla logo. Ma efekt tylko wtedy, gdy określono (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Zwraca:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


Pobiera lub ustawia pełny adres hiperłącza dla logo. Ma efekt tylko wtedy, gdy określono (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Określa jakość obrazów JPEG. Domyślnie 95.

**Zwraca:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Określa jakość obrazów JPEG. Domyślnie 95.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ta właściwość nie obsługuje przypisywania obiektów typu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Ta właściwość nie obsługuje przypisywania obiektów typu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |