---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考
description: 取得一個值，用於指示文字是否在渲染時不使用連字。當設定為 true，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 false。
type: docs
weight: 326
url: /zh-hant/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() 方法

取得一個值，用於指示文字是否在渲染時不使用連字。當設定為 **true** 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 **false**。

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // 在文字渲染中停用連字

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## 另請參閱

* 類別 [SVGOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)