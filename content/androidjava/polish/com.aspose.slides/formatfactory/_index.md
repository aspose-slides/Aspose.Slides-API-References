---
title: FormatFactory
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Umożliwia tworzenie formatów poprzez interfejs COM.
type: docs
url: /pl/com.aspose.slides/formatfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Umożliwia tworzenie formatów poprzez interfejs COM.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getInstance()](#getInstance--) | Instancja statyczna fabryki formatu. |
| [createPortionFormat()](#createPortionFormat--) | Tworzy nowy [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Tworzy nowy [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Tworzy nowy [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Instancja statyczna fabryki formatu. Tylko do odczytu [FormatFactory](../../com.aspose.slides/formatfactory).

**Zwraca:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Tworzy nowy [IPortionFormat](../../com.aspose.slides/iportionformat).

**Zwraca:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Nowy format fragmentu.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Tworzy nowy [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Zwraca:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Nowy format akapitu.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Tworzy nowy [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Zwraca:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Nowy format ramki tekstowej.