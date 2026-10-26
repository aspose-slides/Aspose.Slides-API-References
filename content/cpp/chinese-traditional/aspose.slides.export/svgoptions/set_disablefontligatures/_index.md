---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定一個值，以指示文字是否在不使用連字的情況下呈現。當設定為 true 時，連字將在輸出中被停用。預設情況下，此屬性設定為 false。
type: docs
weight: 339
url: /zh-hant/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) 方法


設定一個值，以指示文字是否在不使用連字的情況下呈現。當設定為 **true** 時，連字將在輸出中被停用。預設情況下，此屬性設定為 **false**。

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // 在文字渲染時停用連字

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## 參見

* 類別 [SVGOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)