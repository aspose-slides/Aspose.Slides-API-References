---
title: IMathBarFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi egy matematikai vonal létrehozását
type: docs
url: /hu/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Lehetővé teszi egy matematikai vonal létrehozását

For COM comparibility
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Matematikai vonalat hoz létre az elemre alkalmazva |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Matematikai vonalat hoz létre az elemre alkalmazva |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

Matematikai vonalat hoz létre az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math elem, amelyre a vonalat alkalmazzák |

**Visszatérési érték:**
[IMathBar](../../com.aspose.slides/imathbar) - új math bar elem
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

Matematikai vonalat hoz létre az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Math elem, amelyre a vonalat alkalmazzák |
| position | int | A vonal pozíciója |

**Visszatérési érték:**
[IMathBar](../../com.aspose.slides/imathbar) - új math bar elem