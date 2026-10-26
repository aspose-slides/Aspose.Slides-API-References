---
title: IMathArrayFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi matematikai tömb létrehozását
type: docs
url: /hu/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

Lehetővé teszi matematikai tömb létrehozását

--------------------

COM kompatibilitáshoz
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | Létrehoz egy matematikai tömböt, és elhelyezi a megadott elemet benne |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | Létrehoz egy matematikai tömböt, és elhelyezi a megadott elemeket benne |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```

Létrehoz egy matematikai tömböt, és elhelyezi a megadott elemet benne

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyet a tömbbe helyez |

**Visszatérési érték:**
[IMathArray](../../com.aspose.slides/imatharray) - új matematikai tömb
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```

Létrehoz egy matematikai tömböt, és elhelyezi a megadott elemeket benne

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematikai elemek, amelyeket a tömbbe helyez |

**Visszatérési érték:**
[IMathArray](../../com.aspose.slides/imatharray) - új matematikai tömb