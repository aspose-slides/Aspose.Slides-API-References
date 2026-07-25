---
title: MarkdownImageSavingHandler
second_title: Aspose.Slides for C++ API リファレンス
description: Markdown エクスポート中に、非 SVG 画像（ビットマップまたはメタファイル）ごとに呼び出されます。 指定されたリンクを使用するには true を返し、 または false を返すとデフォルトの保存ロジックが適用されます。
type: docs
weight: 300
url: /ja/aspose.slides.export/markdownsaveoptions/markdownimagesavinghandler/
---
## MarkdownImageSavingHandler typedef

Markdown エクスポート中に、各非 SVG 画像（ビットマップまたはメタファイル）に対して呼び出されます。

 Return **true** を返すと、指定された *link* を使用します、

 or **false** を返すと、デフォルトの保存ロジックが適用されます。

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<IImage>, ImageFormat, System::String&)>
```


## 参照

* クラス [MarkdownSaveOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)