---
title: IMathArrayFactory
second_title: Aspose.Slides for Android の Java API リファレンス
description: 数式配列を作成できます
type: docs
url: /ja/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

数式配列を作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | 数式配列を作成し、指定された要素を配置します |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | 数式配列を作成し、指定された要素を配置します |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```


数式配列を作成し、指定された要素を配置します

**パラメータ:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 配列に配置する数式要素 |

**戻り値:**
[IMathArray](../../com.aspose.slides/imatharray) - 新しい数式配列