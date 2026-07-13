---
title: IOverridableText
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Reprezentuje nadpisywalny tekst dla wykresu.
type: docs
url: /pl/com.aspose.slides/ioverridabletext/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Reprezentuje nadpisywalny tekst dla wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Może zawierać bogato sformatowany tekst. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicjalizuje TextFrameForOverriding tekstem w parametrze "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Może zawierać bogato sformatowany tekst. Jeśli ta właściwość nie jest nullem, to ta sformatowana wartość tekstu zastępuje automatycznie generowany tekst. Automatycznie generowany tekst jest domyślną właściwością etykiety danych, etykiety jednostki wyświetlania osi wartości, tytułu osi, tytułu wykresu, etykiety linii trendu. Automatycznie generowany tekst jest formatowany za pomocą właściwości IFormattedTextContainer.TextFormat. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Inicjalizuje TextFrameForOverriding tekstem w parametrze "text". Jeśli TextFrameForOverriding jest już zainicjalizowany, po prostu zmienia jego tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst dla nowego TextFrameForOverriding. |

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe) - Text frame [ITextFrame](../../com.aspose.slides/itextframe)