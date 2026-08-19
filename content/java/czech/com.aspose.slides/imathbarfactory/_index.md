---
title: IMathBarFactory
second_title: Aspose.Slides for Java API Reference
description: Umožňuje vytvořit matematický pruh
type: docs
url: /cs/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Umožňuje vytvořit matematický pruh

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Vytvoří matematický pruh aplikací na prvek |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Vytvoří matematický pruh aplikací na prvek |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```


Vytvoří matematický pruh aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se má pruh aplikovat |

**Návratová hodnota:**
[IMathBar](../../com.aspose.slides/imathbar) - nový prvek matematického pruhu
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```


Vytvoří matematický pruh aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Matematický prvek, na který se má pruh aplikovat |
| position | int | Pozice pruhu |

**Návratová hodnota:**
[IMathBar](../../com.aspose.slides/imathbar) - nový prvek matematického pruhu