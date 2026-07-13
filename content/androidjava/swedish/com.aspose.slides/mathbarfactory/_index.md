---
title: MathBarFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa en math bar
type: docs
url: /sv/com.aspose.slides/mathbarfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathBarFactory](../../com.aspose.slides/imathbarfactory)
```
public class MathBarFactory implements IMathBarFactory
```

Tillåter att skapa en math bar

--------------------

För COM-kompatibilitet
## Konstruktorer

| Constructor | Beskrivning |
| --- | --- |
| [MathBarFactory()](#MathBarFactory--) |  |
## Metoder

| Method | Beskrivning |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Skapa en math bar genom att tillämpa på elementet |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Skapa en math bar genom att tillämpa på elementet |
### MathBarFactory() {#MathBarFactory--}
```
public MathBarFactory()
```


### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public final IMathBar createMathBar(IMathElement element)
```


Skapa en math bar genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | mattelement att applicera stapeln på |

**Returnerar:**
[IMathBar](../../com.aspose.slides/imathbar) - nytt math bar-element
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public final IMathBar createMathBar(IMathElement element, int position)
```


Skapa en math bar genom att tillämpa på elementet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mattelement att applicera stapeln på |
| position | int | Position för stapeln |

**Returnerar:**
[IMathBar](../../com.aspose.slides/imathbar) - nytt math bar-element