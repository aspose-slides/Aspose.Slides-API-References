---
title: get_SignTime()
second_title: Aspose.Slides C++ API 參考文件
description: "文件簽署的時間。唯讀 System::DateTime."
type: docs
weight: 27
url: /zh-hant/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() 方法


文件簽署的時間。唯讀 [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(u"Signature check: {0}, Signing time: {1}",
        (signature->get_IsValid() ? u"VALID" : u"INVALID"),
        signature->get_SignTime()
    );
}
```

## 另請參閱

* 類別 [DateTime](../../../system/datetime/)
* 類別 [DigitalSignature](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)