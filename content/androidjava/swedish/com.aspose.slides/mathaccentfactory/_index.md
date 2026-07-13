---
title: MathAccentFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa en matteaccent
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

Tillåter att skapa en matteaccent

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Skapar en matteaccent som tillämpas på ett angivet matteelement med standardaccentteckenvärde |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Skapar en matteaccent som tillämpas på ett angivet matteelement |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Skapar en matteaccent som tillämpas på ett angivet matteelement med standardaccentteckenvärde

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matteelement att applicera accent på |

**Returnerar:**
[IMathAccent](../../com.aspose.slides/imathaccent) - ny matteaccent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Skapar en matteaccent som tillämpas på ett angivet matteelement

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matteelement att applicera accent på |
| accentCharacter | char | accenttecken |

**Returnerar:**
[IMathAccent](../../com.aspose.slides/imathaccent) - ny matteaccent