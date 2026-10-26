---
title: get_SignTime()
second_title: Aspose.Slides C++ API 参考
description: "文档签名的时间。只读 System::DateTime."
type: docs
weight: 27
url: /zh/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() 方法


文档签名的时间。只读 [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## 备注



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

## 另请参阅

* 类 [DateTime](../../../system/datetime/)
* 类 [DigitalSignature](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)