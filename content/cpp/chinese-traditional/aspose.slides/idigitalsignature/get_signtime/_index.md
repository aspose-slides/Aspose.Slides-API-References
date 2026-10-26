---
title: get_SignTime()
second_title: Aspose.Slides for C++ API 參考文件
description: "文件簽署的時間。唯讀 System::DateTime."
type: docs
weight: 27
url: /zh-hant/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() 方法


文件簽署的時間。唯讀 [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## 另請參閱

* 類別 [DateTime](../../../system/datetime/)
* 類別 [IDigitalSignature](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)