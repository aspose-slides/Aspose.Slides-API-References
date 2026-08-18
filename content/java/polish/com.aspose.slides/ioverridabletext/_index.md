---
title: IOverridableText
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje tekst, który można nadpisać, dla wykresu.
type: docs
url: /pl/com.aspose.slides/ioverridabletext/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Reprezentuje tekst, który można nadpisać, dla wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Może zawierać bogato formatowany tekst. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicjalizuje TextFrameForOverriding tekstem w parametrze "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Może zawierać bogato formatowany tekst. Jeśli ta właściwość nie jest null, to ta sformatowana wartość tekstu nadpisuje automatycznie generowany tekst. Automatycznie generowany tekst jest implicytną właściwością etykiety danych, etykiety jednostki wyświetlania osi wartości, tytułu osi, tytułu wykresu, etykiety linii trendu. Automatycznie generowany tekst jest formatowany przy użyciu właściwości IFormattedTextContainer.TextFormat. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Inicjalizuje TextFrameForOverriding tekstem w parametrze "text". Jeśli TextFrameForOverriding jest już zainicjowany, po prostu zmienia jego tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst dla nowego TextFrameForOverriding. |

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe) - ramka tekstowa [ITextFrame](../../com.aspose.slides/itextframe)