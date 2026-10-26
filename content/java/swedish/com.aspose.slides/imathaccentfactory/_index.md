---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: Tillåter att skapa en matematisk accent
type: docs
url: /sv/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Tillåter att skapa en matematisk accent

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Skapar en matematisk accent som tillämpas på ett specificerat matematikelement med standardvärdet för accenttecken |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Skapar en matematisk accent som tillämpas på ett specificerat matematikelement |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


Skapar en matematisk accent som tillämpas på ett specificerat matematikelement med standardvärdet för accenttecken

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikelement som accent ska appliceras på |

**Returnerar:**
[IMathAccent](../../com.aspose.slides/imathaccent) - ny matematisk accent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMMathElement element, char accentCharacter)
```


Skapar en matematisk accent som tillämpas på ett specificerat matematikelement

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikelement som accent ska appliceras på |
| accentCharacter | char | accenttecken |

**Returnerar:**
[IMathAccent](../../com.aspose.slides/imathaccent) - ny matematisk accent