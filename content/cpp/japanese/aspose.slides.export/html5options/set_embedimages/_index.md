---
title: set_EmbedImages()
second_title: Aspose.Slides for C++ API リファレンス
description: 画像の埋め込みオプションを設定します。bool を書き込みます。
type: docs
weight: 66
url: /ja/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) メソッド

画像の埋め込みオプションを設定します。**bool** を書き込みます。

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
```

## 備考

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 参照

* クラス [Html5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)