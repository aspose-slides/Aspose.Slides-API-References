---
title: IOverridableText
second_title: Aspose.Slides for Java API リファレンス
description: チャートのオーバーライド可能なテキストを表します。
type: docs
url: /ja/com.aspose.slides/ioverridabletext/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

チャートのオーバーライド可能なテキストを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | リッチ形式のテキストを含めることができます。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | パラメーター "text" のテキストで TextFrameForOverriding を初期化します。 |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


リッチ形式のテキストを含めることができます。このプロパティが null でない場合、このフォーマットされたテキスト値は自動生成テキストを上書きします。自動生成テキストは、データラベル、値軸の表示単位ラベル、軸タイトル、チャートタイトル、トレンドラインのラベルの暗黙的なプロパティです。自動生成テキストは IFormattedTextContainer.TextFormat プロパティでフォーマットされます。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


パラメーター "text" のテキストで TextFrameForOverriding を初期化します。TextFrameForOverriding がすでに初期化されている場合は、単にそのテキストを変更します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 新しい TextFrameForOverriding のテキスト。 |

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe) - Text frame [ITextFrame](../../com.aspose.slides/itextframe)