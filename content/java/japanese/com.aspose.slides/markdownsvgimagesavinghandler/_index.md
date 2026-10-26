---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API リファレンス
description: markdown SVG 画像保存ハンドラを表します \#SvgImageSavingDelegate.SvgImageSavingDelegate イベントの。
type: docs
url: /ja/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

markdown SVG 画像保存ハンドラを表します \#SvgImageSavingDelegate.SvgImageSavingDelegate イベントの。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Markdown エクスポート中に各 SVG 画像が呼び出されます。 |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Markdown エクスポート中に各 SVG 画像が呼び出されます。true を返すと指定されたリンクを使用し、false を返すとデフォルトの保存ロジックが適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | エクスポートされる SVG 画像です。 |
| link | java.lang.String[] | true を返すと使用される Markdown リンクです。 |

**戻り値:**
boolean