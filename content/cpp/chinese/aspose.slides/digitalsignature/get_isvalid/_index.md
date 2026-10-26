---
title: get_IsValid()
second_title: Aspose.Slides for C++ API 参考
description: 如果此数字签名有效且文档未被篡改，此值为 true。只读 bool.
type: docs
weight: 14
url: /zh/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() 方法


如果此数字签名有效且文档未被篡改，则此值为 true。只读 **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
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

## 另请参见

* 类 [DigitalSignature](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)