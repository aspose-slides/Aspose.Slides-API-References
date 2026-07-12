---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathLimit
type: docs
url: /ja/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

IMathLimit を作成できる

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | IMathLimit を作成します |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 下部に制限を持つ IMathLimit を作成します |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


IMathLimit を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 制限を適用するベース引数 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 制限要素 |
| upperLimit | boolean | 制限の配置を上部に設定します |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新しい math limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


下部に制限を持つ IMathLimit を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 制限を適用するベース引数 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 制限要素 |

**戻り値:**
[IMathLimit](../../com.aspose.slides/imathlimit) - 新しい math limit