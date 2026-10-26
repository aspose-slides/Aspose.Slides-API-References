---
title: MathAccentFactory
second_title: Aspose.Slides dla Androida za pośrednictwem odniesienia API Java
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

Dla zgodności z COM
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego ma być zastosowany akcent |

**Zwraca:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nowy akcent matematyczny
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Tworzy akcent matematyczny stosowany do określonego elementu matematycznego

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego ma być zastosowany akcent |
| accentCharacter | char | znak akcentu |

**Zwraca:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nowy akcent matematyczny