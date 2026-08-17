---
title: IMathRadicalFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create math radical
type: docs
url: /ja/com.aspose.slides/imathradicalfactory/
---```
public interface IMathRadicalFactory
```

数式の根号を作成できます

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 数式の根号を作成します |

### createMathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```

数式の根号を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 根号を適用するベース引数 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 次数の値 |

**戻り値:**
[IMathRadical](../../com.aspose.slides/imathradical) - 新しい根号要素