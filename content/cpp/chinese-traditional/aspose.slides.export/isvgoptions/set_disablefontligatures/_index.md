---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考
description: 設定一個值，以指示文字在渲染時是否不使用連字。當設定為 true 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 false。
type: docs
weight: 339
url: /zh-hant/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISSVGOptions::set_DisableFontLigatures(bool) 方法


設定一個值，以指示文字是否在渲染時不使用連字。當設定為 **true** 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 **false**。

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // 停用文字渲染中的連字

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## 另請參閱

* 類別 [ISVGOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)