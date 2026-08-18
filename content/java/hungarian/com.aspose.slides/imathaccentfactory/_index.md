---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Hivatkozás
description: Lehetővé teszi matematikai akcentus létrehozását
type: docs
url: /hu/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Lehetővé teszi matematikai akcentus létrehozását

--------------------

COM kompatibilitáshoz
## Metódusok

| Method | Description |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Létrehoz egy matematikai akcentust, amely egy megadott matematikai elemre alkalmazza az alapértelmezett akcentus karakter értékkel |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Létrehoz egy matematikai akcentust, amely egy megadott matematikai elemre alkalmaz |

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Létrehoz egy matematikai akcentust, amely egy megadott matematikai elemre alkalmazza az alapértelmezett akcentus karakter értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyre az akcentust alkalmazzák |

**Visszatérési érték:**
[IMathAccent](../../com.aspose.slides/imathaccent) - új matematikai akcentus

### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Létrehoz egy matematikai akcentust, amely egy megadott matematikai elemre alkalmaz

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyre az akcentust alkalmazzák |
| accentCharacter | char | akcentus karakter |

**Visszatérési érték:**
[IMathAccent](../../com.aspose.slides/imathaccent) - új matematikai akcentus