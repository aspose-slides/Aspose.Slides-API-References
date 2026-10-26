---
title: get_Password()
second_title: Aspose.Slides for C++ API 參考
description: "取得密碼。請閱讀 System::String."
type: docs
weight: 105
url: /zh-hant/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() 方法


取得密碼。閱讀 [System::String](../../../system/string/)。

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## 備註


密碼。 

以下範例程式碼顯示如何開啟受密碼保護的 PowerPoint [Presentation](../../presentation/)。 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [LoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)