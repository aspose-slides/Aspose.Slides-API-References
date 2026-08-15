---
title: get_IsValid()
second_title: Aspose.Slides for C++ API 參考
description: 如果此數位簽章有效且文件未被竄改，此值將為 true。唯讀 bool。
type: docs
weight: 14
url: /zh-hant/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() 方法


如果此數位簽章有效且文件未被竄改，此值將為 true。唯讀 **bool**。

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## 另請參閱

* 類別 [DigitalSignature](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)