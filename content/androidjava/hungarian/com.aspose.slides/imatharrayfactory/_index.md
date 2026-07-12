---
title: IMathArrayFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi egy matematika tömb létrehozását
type: docs
url: /hu/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

Lehetővé teszi egy matematika tömb létrehozását

--------------------

COM kompatibilitáshoz
## Módszerek

| Method | Description |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | Létrehoz egy matematika tömböt, és elhelyezi benne a megadott elemet |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | Létrehoz egy matematika tömböt, és elhelyezi benne a megadott elemeket |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```

Létrehoz egy matematika tömböt, és elhelyezi benne a megadott elemet

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematika elem, amelyet a tömbbe helyez |

**Visszatérési érték:**
[IMathArray](../../com.aspose.slides/imatharray) - új matematika tömb
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```

Létrehoz egy matematika tömböt, és elhelyezi benne a megadott elemeket

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematika elemek, amelyek a tömbbe kerülnek |

**Visszatérési érték:**
[IMathArray](../../com.aspose.slides/imatharray) - új matematika tömb