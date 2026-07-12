---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi egy matematikai elválasztó létrehozását
type: docs
url: /hu/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Lehetővé teszi egy matematikai elválasztó létrehozását

--------------------

A COM kompatibilitáshoz
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Matematikai elválasztó létrehozása az elemre alkalmazva |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Matematikai elválasztó létrehozása az elemre alkalmazva |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```


Matematikai elválasztó létrehozása az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyre az elválasztót alkalmazni kell |

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
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematikai elemek, amelyekre az elválasztót alkalmazni kell |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - új matematikai elválasztó