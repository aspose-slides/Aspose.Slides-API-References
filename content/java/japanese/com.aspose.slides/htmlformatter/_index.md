---
title: HtmlFormatter
second_title: Aspose.Slides for Java API リファレンス
description: HTML ファイルテンプレートを表します。
type: docs
url: /ja/com.aspose.slides/htmlformatter/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)  
```
public final class HtmlFormatter implements IHtmlFormatter
```

HTML ファイルテンプレートを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | シンプルなドキュメントビュー（スライドが上下に並んだシーケンス）用の HTML フォーマッタを作成して返します。 |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | スライドが順番に表示されるシンプルなスライドショー HTML 用のフォーマッタを作成して返します。 |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | カスタムコールバック駆動の HTML 生成用フォーマッタを作成して返します。 |

### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

シンプルなドキュメントビュー（スライドが上下に並んだシーケンス）用の HTML フォーマッタを作成して返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| css | java.lang.String | このファイルの CSS を指定します。 |
| showSlideTitle | boolean | スライド画像の上にタイトルがある場合、タイトルを追加します。 |

**戻り値:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

スライドが順番に表示されるシンプルなスライドショー HTML 用のフォーマッタを作成して返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| css | java.lang.String | 使用する CCS ファイルの URL を指定します。 |
| showSlideTitle | boolean | スライド画像の上にタイトルがある場合、タイトルを追加します。 |

**戻り値:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.

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
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.