---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android の Java API リファレンス
description: ImageSavingDelegate.ImageSavingDelegate イベントの Markdown 画像保存ハンドラを表します。
type: docs
url: /ja/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

ImageSavingDelegate.ImageSavingDelegate イベントの Markdown 画像保存ハンドラを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Markdown エクスポート中に、SVG 以外の画像（ビットマップまたはメタファイル）ごとに呼び出されます。 |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Markdown エクスポート中に、SVG 以外の画像（ビットマップまたはメタファイル）ごとに呼び出されます。true を返すと指定されたリンクを使用し、false を返すとデフォルトの保存ロジックが適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | エクスポートされる画像（ビットマップまたはメタファイル）。 |
| format | int | 画像フォーマット。 |
| link | java.lang.String[] | true を返す場合に使用する Markdown リンク。 |

**戻り値:**
boolean