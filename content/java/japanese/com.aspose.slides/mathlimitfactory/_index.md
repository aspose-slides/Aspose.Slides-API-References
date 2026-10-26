---
title: MathLimitFactory
second_title: Aspose.Slides for Java API リファレンス
description: IMathLimit を作成できます
type: docs
url: /ja/com.aspose.slides/mathlimitfactory/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)  
```
public class MathLimitFactory implements IMathLimitFactory
```

IMathLimit を作成できます

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | IMathLimit を作成します |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 下部に制限付きの IMathLimit を作成します |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```

### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

IMathLimit を作成します

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 制限を適用するベース引数 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 制限要素 |
| upperLimit | boolean | 上部に制限を配置します |

**戻り値:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - 新しい math limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

下部に制限付きの IMathLimit を作成します

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 制限を適用するベース引数 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 制限要素 |

**戻り値:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - 新しい math limit