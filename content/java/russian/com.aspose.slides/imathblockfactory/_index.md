---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math block
type: docs
url: /ru/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Позволяет создавать математический блок

--------------------

Для совместимости с COM
## Methods

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Создать математический блок |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Создать математический блок и разместить в нём элемент |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Создать математический блок и разместить в нём элементы |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Создать математический блок

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - новый математический блок
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Создать математический блок и разместить в нём элемент

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Математический элемент |

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - новый математический блок
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Создать математический блок и разместить в нём элементы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | математические элементы |

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - новый математический блок