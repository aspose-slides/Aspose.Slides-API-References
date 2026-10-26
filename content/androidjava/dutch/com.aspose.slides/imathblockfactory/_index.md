---
title: IMathBlockFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe een wiskundig blok te maken
type: docs
url: /nl/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Staat toe een wiskundig blok te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Maak een wiskundig blok |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Maak een wiskundig blok en plaats het element erin |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Maak een wiskundig blok en plaats elementen erin |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Maak een wiskundig blok

**Retour:**
[IMathBlock](../../com.aspose.slides/imathblock) - nieuw wiskundig blok
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Maak een wiskundig blok en plaats het element erin

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Een wiskundig element |

**Retour:**
[IMathBlock](../../com.aspose.slides/imathblock) - nieuw wiskundig blok
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Maak een wiskundig blok en plaats elementen erin

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | wiskundige elementen |

**Retour:**
[IMathBlock](../../com.aspose.slides/imathblock) - nieuw wiskundig blok