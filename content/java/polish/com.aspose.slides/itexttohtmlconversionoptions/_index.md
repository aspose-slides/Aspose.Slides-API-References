---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Opcje wyodrębniania HTML z tekstu Pptx.
type: docs
url: /pl/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Opcje wyodrębniania HTML z tekstu Pptx.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Zwraca lub ustawia wartość, wskazując, czy nagłówki Clipboard powinny być dodane. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Zwraca lub ustawia wartość, wskazując, czy nagłówki Clipboard powinny być dodane. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Zwraca lub ustawia dziedziczoną głębokość właściwości tekstu. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Zwraca lub ustawia dziedziczoną głębokość właściwości tekstu. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Zwraca lub ustawia obiekt wywołania zwrotnego, który kontroluje, jak obiekt zewnętrzny będzie przechowywany. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Zwraca lub ustawia obiekt wywołania zwrotnego, który kontroluje, jak obiekt zewnętrzny będzie przechowywany. |
| [getEncodingName()](#getEncodingName--) | Zwraca lub ustawia nazwę kodowania html. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Zwraca lub ustawia nazwę kodowania html. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Zwraca lub ustawia wartość, wskazując, czy nagłówki Clipboard powinny być dodane. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Zwraca lub ustawia wartość, wskazując, czy nagłówki Clipboard powinny być dodane. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Zwraca lub ustawia dziedziczoną głębokość właściwości tekstu. Odczyt/zapis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Zwraca:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Zwraca lub ustawia dziedziczoną głębokość właściwości tekstu. Odczyt/zapis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Zwraca lub ustawia obiekt wywołania zwrotnego, który kontroluje, jak obiekt zewnętrzny będzie przechowywany. Odczyt/zapis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Zwraca:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Zwraca lub ustawia obiekt wywołania zwrotnego, który kontroluje, jak obiekt zewnętrzny będzie przechowywany. Odczyt/zapis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Zwraca lub ustawia nazwę kodowania html. Ta wartość zostanie zapisana do wygenerowanego pliku HTML, ale to zależy od wywołującego, aby zapewnić, że plik zostanie zapisany w tym kodowaniu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Zwraca lub ustawia nazwę kodowania html. Ta wartość zostanie zapisana do wygenerowanego pliku HTML, ale to zależy od wywołującego, aby zapewnić, że plik zostanie zapisany w tym kodowaniu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |