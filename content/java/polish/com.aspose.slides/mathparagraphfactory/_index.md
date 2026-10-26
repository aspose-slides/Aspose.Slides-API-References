---
title: MathParagraphFactory
second_title: Odwołanie do API Aspose.Slides dla Javy
description: Umożliwia tworzenie akapitu matematycznego
type: docs
url: /pl/com.aspose.slides/mathparagraphfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Umożliwia tworzenie akapitu matematycznego

--------------------

Dla zgodności z COM
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Utwórz pusty akapit matematyczny |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Tworzy akapit matematyczny i umieszcza w nim określony blok matematyczny |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Utwórz pusty akapit matematyczny

**Zwraca:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nowy akapit matematyczny
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Tworzy akapit matematyczny i umieszcza w nim określony blok matematyczny

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | blok matematyczny do umieszczenia w akapicie |

**Zwraca:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nowy akapit matematyczny