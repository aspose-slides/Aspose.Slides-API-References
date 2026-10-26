---
title: MathAccentFactory
second_title: Aspose.Slides pro Java API Reference
description: Umožňuje vytvořit matematický akcent
type: docs
url: /cs/com.aspose.slides/mathaccentfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Umožňuje vytvořit matematický akcent

--------------------

Pro kompatibilitu s COM
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou znaku akcentu |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Vytvoří matematický akcent aplikovaný na zadaný matematický prvek |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
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
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Vytvoří matematický akcent aplikovaný na zadaný matematický prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se aplikuje akcent |
| accentCharacter | char | znak akcentu |

**Návratová hodnota:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nový matematický akcent