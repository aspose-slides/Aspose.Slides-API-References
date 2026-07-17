---
title: get_SignTime()
second_title: Aspose.Slides for C++ API 参考
description: "文档签署的时间。只读 System::DateTime."
type: docs
weight: 27
url: /zh/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() 方法

文档签署的时间。只读 [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## 另见

* 类 [DateTime](../../../system/datetime/)
* 类 [IDigitalSignature](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)