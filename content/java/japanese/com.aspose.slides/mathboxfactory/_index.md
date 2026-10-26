---
title: MathBoxFactory
second_title: Aspose.Slides の Java API リファレンス
description: 数式ボックスを作成できるようにします
type: docs
url: /ja/com.aspose.slides/mathboxfactory/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathBoxFactory](../../com.aspose.slides/imathboxfactory)
```
public class MathBoxFactory implements IMathBoxFactory
```

数式ボックスを作成できます

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathBoxFactory()](#MathBoxFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathBox(IMathElement element)](#createMathBox-com.aspose.slides.IMathElement-) | 要素に適用して数式ボックスを作成します |
### MathBoxFactory() {#MathBoxFactory--}
```
public MathBoxFactory()
```


### createMathBox(IMathElement element) {#createMathBox-com.aspose.slides.IMathElement-}
```
public final IMathBox createMathBox(IMathElement element)
```


要素に適用して数式ボックスを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ボックスを適用する数式要素 |

**戻り値:**
[IMathBox](../../com.aspose.slides/imathbox) - 新しいボックス要素