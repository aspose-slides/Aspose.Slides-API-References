---
title: set_OutputPath()
second_title: Aspose.Slides for C++ API リファレンス
description: "外部リソースを格納する場所を決定します。System::Stringを書き込みます。"
type: docs
weight: 92
url: /ja/aspose.slides.export/html5options/set_outputpath/
---
## Html5Options::set_OutputPath(System::String) メソッド


外部リソースを格納する場所を決定します。[System::String](../../../system/string/)を書き込みます。

```cpp
void Aspose::Slides::Export::Html5Options::set_OutputPath(System::String value) override
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 参照

* クラス [String](../../../system/string/)
* クラス [Html5Options](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)