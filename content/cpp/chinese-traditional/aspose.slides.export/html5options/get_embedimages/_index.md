---
title: get_EmbedImages()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回圖像嵌入選項。讀取 bool。
type: docs
weight: 53
url: /zh-hant/aspose.slides.export/html5options/get_embedimages/
---
## Html5Options::get_EmbedImages() 方法


返回圖像嵌入選項。讀取 **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_EmbedImages() override
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 另請參閱

* 類別 [Html5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)