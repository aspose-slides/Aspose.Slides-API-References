---
title: get_OutputPath()
second_title: Aspose.Slides for C++ API 參考
description: "確定外部資源應儲存的位置。閱讀 System::String."
type: docs
weight: 79
url: /zh-hant/aspose.slides.export/html5options/get_outputpath/
---
## Html5Options::get_OutputPath() 方法


確定外部資源應存放的位置。閱讀 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::Html5Options::get_OutputPath() override
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(true);
html5Options->set_OutputPath(u"the_desired_path");
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [Html5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)