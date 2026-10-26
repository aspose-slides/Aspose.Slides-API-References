---
title: set_EmbedImages()
second_title: Aspose.Slides C++ API 參考
description: 設定圖像嵌入選項。寫入 bool。
type: docs
weight: 66
url: /zh-hant/aspose.slides.export/html5options/set_embedimages/
---
## Html5Options::set_EmbedImages(bool) 方法


設定圖像嵌入選項。寫入 **bool**。

```cpp
void Aspose::Slides::Export::Html5Options::set_EmbedImages(bool value) override
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_EmbedImages(false);
pres->Save(u"demo-linked-images.html", SaveFormat::Html5, html5Options);
```

## 另見

* 類別 [Html5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)