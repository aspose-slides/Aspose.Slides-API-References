---
title: FormatFactory
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: COM インターフェイスを介してフォーマットを作成できます。
type: docs
url: /ja/com.aspose.slides/formatfactory/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
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
| [createPortionFormat()](#createPortionFormat--) | 新しい[IPortionFormat](../../com.aspose.slides/iportionformat)を作成します。 |
| [createParagraphFormat()](#createParagraphFormat--) | 新しい[IParagraphFormat](../../com.aspose.slides/iparagraphformat)を作成します。 |
| [createTextFrameFormat()](#createTextFrameFormat--) | 新しい[ITextFrameFormat](../../com.aspose.slides/itextframeformat)を作成します。 |

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

新しい[IPortionFormat](../../com.aspose.slides/iportionformat)を作成します。

**戻り値:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - 新しいポーション形式。

### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

新しい[IParagraphFormat](../../com.aspose.slides/iparagraphformat)を作成します。

**戻り値:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 新しい段落形式。

### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

新しい[ITextFrameFormat](../../com.aspose.slides/itextframeformat)を作成します。

**戻り値:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - 新しいテキストフレーム形式。