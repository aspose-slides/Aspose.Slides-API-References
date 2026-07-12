---
title: IMathAccentFactory
second_title: Aspose.Slides für Android über Java API-Referenz
description: Ermöglicht das Erstellen eines mathematischen Akzents
type: docs
url: /de/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Ermöglicht das Erstellen eines mathematischen Akzents

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathe-Element angewendet wird, mit dem Standard-Akzentzeichenwert |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathe-Element angewendet wird |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathe-Element angewendet wird, mit dem Standard-Akzentzeichenwert

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, auf das der Akzent angewendet wird |

**Rückgabewert:**
[IMathAccent](../../com.aspose.slides/imathaccent) - neuer mathematischer Akzent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Erstellt einen mathematischen Akzent, der auf ein angegebenes Mathe-Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, auf das der Akzent angewendet wird |
| accentCharacter | char | Akzentzeichen |

**Rückgabewert:**
[IMathAccent](../../com.aspose.slides/imathaccent) - neuer mathematischer Akzent