---
title: HtmlFormatter
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: HTML ファイルテンプレートを表します。
type: docs
url: /ja/com.aspose.slides/htmlformatter/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

HTML ファイルテンプレートを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | スライドが上下に連なるシンプルな文書ビュー用の HTML フォーマッタを作成して返します。 |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | スライドが順番に表示されるシンプルなスライドショー HTML 用のフォーマッタを作成して返します。 |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | カスタムコールバック駆動の HTML 生成用フォーマッタを作成して返します。 |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

スライドが上下に連なるシンプルな文書ビュー用の HTML フォーマッタを作成して返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| css | java.lang.String | このファイルの CSS を指定します。 |
| showSlideTitle | boolean | スライド画像の上にタイトルがある場合、スライドタイトルを追加します。 |

**戻り値:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) オブジェクト。
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

スライドが順番に表示されるシンプルなスライドショー HTML 用のフォーマッタを作成して返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| css | java.lang.String | 使用される CCS ファイルの URL を指定します。 |
| showSlideTitle | boolean | スライド画像の上にタイトルがある場合、スライドタイトルを追加します。 |

**戻り値:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) オブジェクト。
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

カスタムコールバック駆動の HTML 生成用フォーマッタを作成して返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | HTML ファイル生成を制御するコールバックインターフェイスです。 |

**戻り値:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - [HtmlFormatter](../../com.aspose.slides/htmlformatter) オブジェクト。