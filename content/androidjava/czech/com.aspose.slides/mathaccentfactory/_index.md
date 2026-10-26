---
title: MathAccentFactory
second_title: Aspose.Slides pro Android prostřednictvím referenční příručky Java API
description: Umožňuje vytvořit matematický akcent
type: docs
url: /cs/com.aspose.slides/mathaccentfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
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


Vytvoří matematický akcent aplikovaný na zadaný matematický prvek s výchozí hodnotou akcentovacího znaku

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se akcent aplikuje |

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se akcent aplikuje |
| accentCharacter | char | akcentovací znak |

**Návratová hodnota:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nový matematický akcent