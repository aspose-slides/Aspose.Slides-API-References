---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: マークダウン画像保存ハンドラを表します（ImageSavingDelegate.ImageSavingDelegate イベント）。
type: docs
url: /ja/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

マークダウン画像保存ハンドラを表します \#ImageSavingDelegate.ImageSavingDelegate イベント。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Markdown エクスポート中に、非 SVG 画像（ビットマップまたはメタファイル）ごとに呼び出されます。 |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Markdown エクスポート中に、非 SVG 画像（ビットマップまたはメタファイル）ごとに呼び出されます。true を返すと指定されたリンクを使用し、false を返すと既定の保存ロジックが適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | エクスポートされる画像（ビットマップまたはメタファイル）。 |
| format | int | 画像のフォーマット。 |
| link | java.lang.String[] | true を返すと使用される Markdown リンク。 |

**戻り値:**
boolean