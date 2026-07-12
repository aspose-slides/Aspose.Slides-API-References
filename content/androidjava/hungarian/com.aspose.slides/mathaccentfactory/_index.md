---
title: MathAccentFactory
second_title: Aspose.Slides Androidhoz Java API referencián keresztül
description: Lehetővé teszi egy matematikai hangsúly létrehozását
type: docs
url: /hu/com.aspose.slides/mathaccentfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Lehetővé teszi egy matematikai hangsúly létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Módszerek

| Módszer | Leírás |
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

Létrehoz egy matematikai hangsúlyt, amely egy megadott matematikai elemre alkalmazza az alapértelmezett hangsúlykaraktert

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a hangsúlyt alkalmazandó matematikai elem |

**Visszatérési érték:**
[IMathAccent](../../com.aspose.slides/imathaccent) - új matematikai hangsúly
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Létrehoz egy matematikai hangsúlyt, amely egy megadott matematikai elemre alkalmazza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a hangsúlyt alkalmazandó matematikai elem |
| accentCharacter | char | hangsúly karakter |

**Visszatérési érték:**
[IMathAccent](../../com.aspose.slides/imathaccent) - új matematikai hangsúly