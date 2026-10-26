---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt je in staat een wiskundig groeperingskarakter te maken
type: docs
url: /nl/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Stelt je in staat een wiskundig groeperingskarakter te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Maakt een wiskundig groeperingskarakter |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Maakt een wiskundig groeperingskarakter |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Maakt een wiskundig groeperingskarakter

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om groeperingskarakter toe te passen |
| character | char | groeperingskarakter |
| position | int | positie van het groeperingskarakter |
| verticalJustification | int | verticale uitlijning |

**Retourwaarde:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nieuw groeperingskarakter element
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Maakt een wiskundig groeperingskarakter

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om groeperingskarakter toe te passen |

**Retourwaarde:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nieuw groeperingskarakter element