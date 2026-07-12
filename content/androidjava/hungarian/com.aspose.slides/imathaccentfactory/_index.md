---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi egy matematikai akcentus létrehozását
type: docs
url: /hu/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Lehetővé teszi egy matematikai akcentus létrehozását

--------------------

COM kompatibilitáshoz
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Létrehozza a meghatározott matematikai elemen alkalmazandó matematikai akcentust az alapértelmezett akcentus karakter értékkel |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Létrehozza a meghatározott matematikai elemre alkalmazandó matematikai akcentust |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Létrehozza a meghatározott matematikai elemen alkalmazandó matematikai akcentust az alapértelmezett akcentus karakter értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem az akcentus alkalmazásához |

**Visszatérési érték:**
[IMathAccent](../../com.aspose.slides/imathaccent) - új matematikai akcentus
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Létrehozza a meghatározott matematikai elemre alkalmazandó matematikai akcentust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem az akcentus alkalmazásához |
| accentCharacter | char | akcentus karakter |

**Visszatérési érték:**
[IMathAccent](../../com.aspose.slides/imathaccent) - új matematikai akcentus