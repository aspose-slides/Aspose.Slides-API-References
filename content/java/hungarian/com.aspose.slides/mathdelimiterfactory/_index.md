---
title: MathDelimiterFactory
second_title: Aspose.Slides Java API hivatkozás
description: Lehetővé teszi egy matematikai elválasztó létrehozását
type: docs
url: /hu/com.aspose.slides/mathdelimiterfactory/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMathDelimiterFactory](../../com.aspose.slides/imathdelimiterfactory)
```
public class MathDelimiterFactory implements IMathDelimiterFactory
```

Lehetővé teszi egy matematikai elválasztó létrehozását

--------------------

A COM kompatibilitáshoz

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathDelimiterFactory()](#MathDelimiterFactory--) |  |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |

### MathDelimiterFactory() {#MathDelimiterFactory--}
```
public MathDelimiterFactory()
```

### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public final IMathDelimiter createMathDelimiter(IMathElement element)
```

Matematikai elválasztót hoz létre az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem az elválasztó alkalmazásához |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - új matematikai elválasztó

### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public final IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Matematikai elválasztót hoz létre az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematikai elemek az elválasztó alkalmazásához |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - új matematikai elválasztó