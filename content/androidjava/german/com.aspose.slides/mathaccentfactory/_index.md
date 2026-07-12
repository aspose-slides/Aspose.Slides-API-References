---
title: MathAccentFactory
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Ermöglicht das Erstellen eines mathematischen Akzents
type: docs
url: /de/com.aspose.slides/mathaccentfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Ermöglicht das Erstellen eines mathematischen Akzents

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element angewendet wird, mit dem Standardwert für das Akzentzeichen |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element angewendet wird |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element angewendet wird, mit dem Standardwert für das Akzentzeichen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathelement, dem das Akzent hinzugefügt wird |

**Rückgabe:**
[IMathAccent](../../com.aspose.slides/imathaccent) - neuer mathematischer Akzent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Erstellt einen mathematischen Akzent, der auf ein angegebenes mathematisches Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathelement, dem das Akzent hinzugefügt wird |
| accentCharacter | char | Akzentzeichen |

**Rückgabe:**
[IMathAccent](../../com.aspose.slides/imathaccent) - neuer mathematischer Akzept