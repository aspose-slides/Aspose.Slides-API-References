---
title: FormatFactory
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Umożliwia tworzenie formatów za pośrednictwem interfejsu COM.
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

Umożliwia tworzenie formatów za pośrednictwem interfejsu COM.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [getInstance()](#getInstance--) | Statyczna instancja fabryki formatów. |
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

Statyczna instancja fabryki formatów. Tylko do odczytu [FormatFactory](../../com.aspose.slides/formatfactory).

**Zwraca:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

Tworzy nowy [IPortionFormat](../../com.aspose.slides/iportionformat).

**Zwraca:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Nowy format porcji.
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