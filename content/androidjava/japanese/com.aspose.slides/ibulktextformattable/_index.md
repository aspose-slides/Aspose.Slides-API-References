---
title: IBulkTextFormattable
second_title: Aspose.Slides for Android via Java API リファレンス
description: 子テキスト要素のフォーマットを一括設定できるオブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/ibulktextformattable/
---```
public interface IBulkTextFormattable
```

子テキスト要素のフォーマットを一括設定できるオブジェクトを表します。

## メソッド

| Method | Description |
| --- | --- |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 定義された部分フォーマットプロパティをすべての要素の部分に設定します。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 定義された段落フォーマットプロパティをすべての要素の段落に設定します。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 定義されたテキストフレームフォーマットプロパティをすべての要素のテキストフレームに設定します。 |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setTextFormat(IPortionFormat source)
```

定義された部分フォーマットプロパティをすべての要素の部分に設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 必要なプロパティが設定されたIPortionFormatオブジェクト。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public abstract void setTextFormat(IParagraphFormat source)
```

定義された段落フォーマットプロパティをすべての要素の段落に設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 必要なプロパティが設定されたIParagraphFormatオブジェクト。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public abstract void setTextFormat(ITextFrameFormat source)
```

定義されたテキストフレームフォーマットプロパティをすべての要素のテキストフレームに設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 必要なプロパティが設定されたITextFrameFormatオブジェクト。 |