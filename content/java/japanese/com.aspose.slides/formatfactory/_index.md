---
title: FormatFactory
second_title: Aspose.Slides の Java API リファレンス
description: COM インターフェイスを介してフォーマットを作成できます。
type: docs
url: /ja/com.aspose.slides/formatfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

COM インターフェイスを介してフォーマットを作成できます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInstance()](#getInstance--) | フォーマットファクトリの静的インスタンスです。 |
| [createPortionFormat()](#createPortionFormat--) | 新しい [IPortionFormat](../../com.aspose.slides/iportionformat) を作成します。 |
| [createParagraphFormat()](#createParagraphFormat--) | 新しい [IParagraphFormat](../../com.aspose.slides/iparagraphformat) を作成します。 |
| [createTextFrameFormat()](#createTextFrameFormat--) | 新しい [ITextFrameFormat](../../com.aspose.slides/itextframeformat) を作成します。 |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

フォーマットファクトリの静的インスタンスです。読み取り専用 [FormatFactory](../../com.aspose.slides/formatfactory)。

**戻り値:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

新しい [IPortionFormat](../../com.aspose.slides/iportionformat) を作成します。

**戻り値:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - 新しい部分フォーマット。
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

新しい [IParagraphFormat](../../com.aspose.slides/iparagraphformat) を作成します。

**戻り値:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 新しい段落フォーマット。
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

新しい [ITextFrameFormat](../../com.aspose.slides/itextframeformat) を作成します。

**戻り値:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - 新しいテキストフレームフォーマット。