---
title: IMathArrayFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math array
type: docs
url: /ja/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

数式配列を作成できる

--------------------

COM互換性のため
## メソッド

| Method | Description |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | 数式配列を作成し、指定された要素を配置します |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | 数式配列を作成し、指定された要素を配置します |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```


数式配列を作成し、指定された要素を配置します

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 配列に配置する数式要素 |

**戻り値:**
[IMathArray](../../com.aspose.slides/imatharray) - 新しい数式配列
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```


数式配列を作成し、指定された要素を配置します

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 配列に配置する数式要素 |

**戻り値:**
[IMathArray](../../com.aspose.slides/imatharray) - 新しい数式配列