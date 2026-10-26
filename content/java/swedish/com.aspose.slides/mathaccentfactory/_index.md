---
title: MathAccentFactory
second_title: Aspose.Slides för Java API-referens
description: Tillåter att skapa en matematisk accent
type: docs
url: /sv/com.aspose.slides/mathaccentfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Tillåter att skapa en matematisk accent

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Skapar en matematisk accent som tillämpas på ett specificerat math-element med standardaccenttecken |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Skapar en matematisk accent som tillämpas på ett specificerat math-element |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Skapar en matematisk accent som tillämpas på ett specificerat math-element med standardaccenttecken

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math-element att applicera accent på |

**Returnerar:**
[IMathAccent](../../com.aspose.slides/imathaccent) - ny matematisk accent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Skapar en matematisk accent som tillämpas på ett specificerat math-element

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math-element att applicera accent på |
| accentCharacter | char | accent-tecken |

**Returnerar:**
[IMathAccent](../../com.aspose.slides/imathaccent) - ny matematisk accent