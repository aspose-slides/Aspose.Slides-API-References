---
title: get_OutputPath()
second_title: Aspose.Slides for C++ API リファレンス
description: "外部リソースが保存される場所を決定します。System::String を参照してください。"
type: docs
weight: 79
url: /ja/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() メソッド


外部リソースを保存する場所を決定します。[System::String](../../../system/string/)を参照してください。

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
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