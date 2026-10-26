---
title: IMathAccentFactory
second_title: Aspose.Slides pro Android přes Java API Reference
description: Umožňuje vytvořit matematický akcent
type: docs
url: /cs/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Umožňuje vytvořit matematický akcent

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou znaku akcentu |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou znaku akcentu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se aplikuje akcent |

**Návratová hodnota:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nový matematický akcent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Vytvoří matematický akcent aplikovaný na zadaný matematický prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se aplikuje akcent |
| accentCharacter | char | znak akcentu |

**Návratová hodnota:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nový matematický akcent