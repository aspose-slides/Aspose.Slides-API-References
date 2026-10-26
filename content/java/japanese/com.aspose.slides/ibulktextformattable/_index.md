---
title: IBulkTextFormattable
second_title: Aspose.Slides for Java API Reference
description: 子テキスト要素の書式を一括設定できるオブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/ibulktextformattable/
---```
public interface IBulkTextFormattable
```

子テキスト要素の書式を一括で設定できるオブジェクトを表します。

## メソッド

| Method | Description |
| --- | --- |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | すべての要素のポーションに対して定義されたポーション書式プロパティを設定します。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | すべての要素の段落に対して定義された段落書式プロパティを設定します。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | すべての要素のテキストフレームに対して定義されたテキストフレーム書式プロパティを設定します。 |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setTextFormat(IPortionFormat source)
```

すべての要素のポーションに対して定義されたポーション書式プロパティを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 必要なプロパティが設定された IPortionFormat オブジェクト。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public abstract void setTextFormat(IParagraphFormat source)
```

すべての要素の段落に対して定義された段落書式プロパティを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 必要なプロパティが設定された IParagraphFormat オブジェクト。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public abstract void setTextFormat(ITextFrameFormat source)
```

すべての要素のテキストフレームに対して定義されたテキストフレーム書式プロパティを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 必要なプロパティが設定された ITextFrameFormat オブジェクト。 |