---
title: MathAccentFactory
second_title: Aspose.Slides dla Java – odniesienie API
description: Umożliwia tworzenie akcentu matematycznego
type: docs
url: /pl/com.aspose.slides/mathaccentfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Umożliwia tworzenie akcentu matematycznego

--------------------

Dla kompatybilności z COM
## Konstruktory

| Constructor | Opis |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Metody

| Method | Opis |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Tworzy akcent matematyczny stosowany do określonego elementu matematycznego |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego ma być zastosowany akcent |

**Zwraca:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nowy akcent matematyczny
### createMathAccent(IMMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Tworzy akcent matematyczny stosowany do określonego elementu matematycznego

**Parametry:**
| Parameter | Type | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego ma być zastosowany akcent |
| accentCharacter | char | znak akcentu |

**Zwraca:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nowy akcent matematyczny