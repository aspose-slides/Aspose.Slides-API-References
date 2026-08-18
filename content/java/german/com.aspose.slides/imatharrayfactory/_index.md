---
title: IMathArrayFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math array
type: docs
url: /de/com.aspose.slides/imatharrayfactory/
---
```
public interface IMathArrayFactory
```

Ermöglicht das Erstellen eines Math-Arrays

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | Creates a math array and places the specified element in it |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | Creates a math array and places specified elements in it |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```

Erstellt ein Math-Array und legt das angegebene Element darin ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Math-Element, das im Array abgelegt werden soll |

**Rückgabewert:**
[IMathArray](../../com.aspose.slides/imatharray) - neues Math-Array
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```

Erstellt ein Math-Array und legt die angegebenen Elemente darin ab

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | Math-Elemente, die im Array abgelegt werden sollen |

**Rückgabewert:**
[IMathArray](../../com.aspose.slides/imatharray) - neues Math-Array