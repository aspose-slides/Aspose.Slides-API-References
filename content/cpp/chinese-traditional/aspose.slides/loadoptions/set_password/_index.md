---
title: set_Password()
second_title: Aspose.Slides for C++ API 參考
description: "設定密碼。寫入 System::String。"
type: docs
weight: 118
url: /zh-hant/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) 方法

設定密碼。寫入 [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## 備註

密碼。 

以下範例程式碼顯示如何開啟受密碼保護的 PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [LoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)