---
title: MathGroupingCharacterFactory
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 数式のグルーピング文字を作成できます
type: docs
url: /ja/com.aspose.slides/mathgroupingcharacterfactory/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

数式のグルーピング文字を作成できます

--------------------

COM 互換性のため
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | 数式のグルーピング文字を作成します |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | 数式のグルーピング文字を作成します |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```

### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

数式のグルーピング文字を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | グルーピング文字を適用する数式要素 |
| character | char | グルーピング文字 |
| position | int | グルーピング文字の位置 |
| verticalJustification | int | 垂直方向の揃え位置 |

**戻り値:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新しいグルーピング文字要素
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

数式のグルーピング文字を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | グルーピング文字を適用する数式要素 |

**戻り値:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - 新しいグルーピング文字要素