---
title: IMathAccentFactory
second_title: Aspose.Slides dla Androida poprzez Java API Reference
description: Umożliwia tworzenie akcentu matematycznego
type: docs
url: /pl/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Umożliwia tworzenie akcentu matematycznego

--------------------

Dla zgodności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Tworzy akcent matematyczny stosowany do określonego elementu matematycznego |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
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
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Tworzy akcent matematyczny stosowany do określonego elementu matematycznego

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego ma być zastosowany akcent |
| accentCharacter | char | znak akcentu |

**Zwraca:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nowy akcent matematyczny