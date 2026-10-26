---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi egy matematikai blokk létrehozását
type: docs
url: /hu/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Lehetővé teszi egy matematikai blokk létrehozását

--------------------

COM kompatibilitásért
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Matematikai blokk létrehozása |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Matematikai blokk létrehozása és az elem elhelyezése benne |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Matematikai blokk létrehozása és elemek elhelyezése benne |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Matematikai blokk létrehozása

**Visszatér:**  
[IMathBlock](../../com.aspose.slides/imathblock) - új matematikai blokk
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Matematikai blokk létrehozása és az elem elhelyezése benne

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Egy matematikai elem |

**Visszatér:**  
[IMathBlock](../../com.aspose.slides/imathblock) - új matematikai blokk
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Matematikai blokk létrehozása és elemek elhelyezése benne

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematikai elemek |

**Visszatér:**  
[IMathBlock](../../com.aspose.slides/imathblock) - új matematikai blokk