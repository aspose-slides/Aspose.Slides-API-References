---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference（Android 用 Java API リファレンス）
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /ja/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Represents the markdown SVG image saving handler of \#SvgImageSavingDelegate.SvgImageSavingDelegate event.
## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Markdown エクスポート中に各 SVG 画像に対して呼び出されます。 |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Markdown エクスポート中に各 SVG 画像に対して呼び出されます。true を返すと指定されたリンクを使用し、false を返すとデフォルトの保存ロジックが適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | エクスポートされる SVG 画像。 |
| link | java.lang.String[] | true を返すと使用する Markdown リンク。 |

**戻り値:**
boolean