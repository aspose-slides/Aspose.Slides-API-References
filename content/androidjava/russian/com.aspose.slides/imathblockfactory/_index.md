---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math block
type: docs
url: /ru/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Позволяет создать блок математических выражений

--------------------

Для совместимости с COM
## Методы

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Создать блок математических выражений |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Создать блок математических выражений и разместить в нём элемент |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Создать блок математических выражений и разместить в нём элементы |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Создать блок математических выражений

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - новый блок математических выражений
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Создать блок математических выражений и разместить в нём элемент

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Элемент математического выражения |

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - новый блок математических выражений
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Создать блок математических выражений и разместить в нём элементы

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | элементы математических выражений |

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - новый блок математических выражений