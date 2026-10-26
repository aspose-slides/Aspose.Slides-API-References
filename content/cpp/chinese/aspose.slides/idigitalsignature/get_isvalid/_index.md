---
title: get_IsValid()
second_title: Aspose.Slides for C++ API 参考
description: 如果此数字签名有效且文档未被篡改，则此值为 true。只读 bool。
type: docs
weight: 14
url: /zh/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() 方法

如果此数字签名有效且文档未被篡改，则此值为 true。只读 **bool**。

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## 另见

* 类 [IDigitalSignature](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)