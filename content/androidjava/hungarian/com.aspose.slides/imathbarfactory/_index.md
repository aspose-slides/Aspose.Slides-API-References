---
title: IMathBarFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi egy matematikai vonal létrehozását
type: docs
url: /hu/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Lehetővé teszi egy matematikai vonal létrehozását

--------------------

A COM kompatibilitás érdekében
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Matematikai vonalat hoz létre az elemre alkalmazva |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Matematikai vonalat hoz létre az elemre alkalmazva |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```


Létrehozza a matematikai vonalat az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem a vonal alkalmazásához |

**Visszatér:**
[IMathBar](../../com.aspose.slides/imathbar) - új matematikai vonal elem
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```


Létrehozza a matematikai vonalat az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem a vonal alkalmazásához |
| position | int | a vonal pozíciója |

**Visszatér:**
[IMathBar](../../com.aspose.slides/imathbar) - új matematikai vonal elem