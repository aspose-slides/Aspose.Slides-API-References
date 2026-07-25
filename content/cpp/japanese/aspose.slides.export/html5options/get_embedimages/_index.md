---
title: get_EmbedImages()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 画像埋め込みオプションを返します。読み取りは bool.
type: docs
weight: 53
url: /ja/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() メソッド

画像埋め込みオプションを返します。読み取り **bool**。

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
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