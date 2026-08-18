---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math delimiter
type: docs
url: /hu/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Lehetővé teszi egy matematikai elválasztó létrehozását

--------------------

COM kompatibilitáshoz
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Matematikai elválasztó létrehozása az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem az elválasztó alkalmazásához |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - új matematikai elválasztó
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Matematikai elválasztó létrehozása az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematikai elemek az elválasztó alkalmazásához |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - új matematikai elválasztó