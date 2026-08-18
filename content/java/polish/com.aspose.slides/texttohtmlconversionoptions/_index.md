---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides dla Java API Reference
description: Opcje wyodrębniania HTML z tekstu Pptx.
type: docs
url: /pl/com.aspose.slides/texttohtmlconversionoptions/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Opcje wyodrębniania HTML z tekstu Pptx.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Zwraca lub ustawia wartość, wskazującą, czy nagłówki Schowka mają być dodane. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Zwraca lub ustawia wartość, wskazującą, czy nagłówki Schowka mają być dodane. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Zwraca lub ustawia dziedziczoną głębokość dla właściwości tekstu. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Zwraca lub ustawia dziedziczoną głębokość dla właściwości tekstu. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Zwraca lub ustawia obiekt wywołania zwrotnego, który kontroluje, jak obiekt zewnętrzny będzie przechowywany. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Zwraca lub ustawia obiekt wywołania zwrotnego, który kontroluje, jak obiekt zewnętrzny będzie przechowywany. |
| [getEncodingName()](#getEncodingName--) | Zwraca lub ustawia nazwę kodowania HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Zwraca lub ustawia nazwę kodowania HTML. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Zwraca lub ustawia wartość, wskazującą, czy nagłówki Schowka mają być dodane. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Zwraca lub ustawia wartość, wskazującą, czy nagłówki Schowka mają być dodane. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Zwraca lub ustawia dziedziczoną głębokość dla właściwości tekstu. Odczyt/zapis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Zwraca:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Zwraca lub ustawia dziedziczoną głębokość dla właściwości tekstu. Odczyt/zapis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Zwraca lub ustawia obiekt wywołania zwrotnego, który kontroluje, jak obiekt zewnętrzny będzie przechowywany. Odczyt/zapis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Zwraca:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Zwraca lub ustawia obiekt wywołania zwrotnego, który kontroluje, jak obiekt zewnętrzny będzie przechowywany. Odczyt/zapis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Zwraca lub ustawia nazwę kodowania HTML. Ta wartość zostanie zapisana do wygenerowanego pliku HTML, ale to od wywołującego zależy, aby plik został zapisany w tym kodowaniu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Zwraca lub ustawia nazwę kodowania HTML. Ta wartość zostanie zapisana do wygenerowanego pliku HTML, ale to od wywołującego zależy, aby plik został zapisany w tym kodowaniu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |