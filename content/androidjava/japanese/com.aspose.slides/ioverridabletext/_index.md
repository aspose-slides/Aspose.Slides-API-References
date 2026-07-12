---
title: IOverridableText
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: チャートのオーバーライド可能なテキストを表します。
type: docs
url: /ja/com.aspose.slides/ioverridabletext/
---
**実装されているすべてのインターフェース:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

チャートのオーバーライド可能なテキストを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | リッチな書式テキストを含めることができます。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | パラメーター "text" のテキストで TextFrameForOverriding を初期化します。 |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

リッチな書式テキストを含めることができます。このプロパティが null でない場合、この書式付きテキストの値は自動生成テキストを上書きします。自動生成テキストはデータ ラベル、値軸の表示単位ラベル、軸タイトル、チャートタイトル、トレンドラインのラベルの暗黙的なプロパティです。自動生成テキストは IFormattedTextContainer.TextFormat プロパティで書式設定されます。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

パラメーター "text" のテキストで TextFrameForOverriding を初期化します。TextFrameForOverriding がすでに初期化されている場合は、そのテキストを単に変更します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しい TextFrameForOverriding のテキスト。 |

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe) - テキスト フレーム [ITextFrame](../../com.aspose.slides/itextframe)