---
title: MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for C++ API リファレンス
description: Markdownエクスポート中に各SVG画像が呼び出されます。指定されたリンクを使用するには true を返し、デフォルトの保存ロジックを適用するには false を返します。
type: docs
weight: 313
url: /ja/aspose.slides.export/markdownsaveoptions/markdownsvgimagesavinghandler/
---
## MarkdownSvgImageSavingHandler typedef

Markdownエクスポート中に各SVG画像が呼び出されます。 

 **true** を返すと、指定された*link* を使用します , 

 または**false** を返すと、デフォルトの保存ロジックが適用されます。

```cpp
using Aspose::Slides::Export::MarkdownSaveOptions::MarkdownSvgImageSavingHandler =  System::MulticastDelegate<bool(System::SharedPtr<ISvgImage>, System::String&)>
```


## 参照

* クラス [MarkdownSaveOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)