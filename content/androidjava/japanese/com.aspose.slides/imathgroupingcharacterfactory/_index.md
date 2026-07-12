---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math grouping character
type: docs
url: /ja/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

数式グルーピング文字を作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | 数式グルーピング文字を作成します |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | 数式グルーピング文字を作成します |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

数式グルーピング文字を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | グルーピング文字を適用する数式要素 |
| character | char | グルーピング文字 |
| position | int | グルーピング文字の位置 |
| verticalJustification | int | 垂直方向の配置 |

**戻り値:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新しいグルーピング文字要素
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

数式グルーピング文字を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | グルーピング文字を適用する数式要素 |

**戻り値:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新しいグルーピング文字要素