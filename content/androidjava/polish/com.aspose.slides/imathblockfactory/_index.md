---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Umożliwia utworzenie bloku matematycznego
type: docs
url: /pl/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Umożliwia utworzenie bloku matematycznego

--------------------

For COM comparibility
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Utwórz blok matematyczny |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Utwórz blok matematyczny i umieść w nim element |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Utwórz blok matematyczny i umieść w nim elementy |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Utwórz blok matematyczny

**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - nowy blok matematyczny
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Utwórz blok matematyczny i umieść w nim element

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Element matematyczny |

**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - nowy blok matematyczny
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Utwórz blok matematyczny i umieść w nim elementy

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementy matematyczne |

**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - nowy blok matematyczny