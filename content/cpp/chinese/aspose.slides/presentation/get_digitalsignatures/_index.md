---
title: get_DigitalSignatures()
second_title: Aspose.Slides for C++ API 参考
description: 返回用于签署演示文稿的签名集合。只读 IDigitalSignatureCollection.
type: docs
weight: 261
url: /zh/aspose.slides/presentation/get_digitalsignatures/
---
## Presentation::get_DigitalSignatures() 方法

返回用于签署演示文稿的签名集合。只读 [IDigitalSignatureCollection](../../idigitalsignaturecollection/)。

```cpp
System::SharedPtr<IDigitalSignatureCollection> Aspose::Slides::Presentation::get_DigitalSignatures() override
```

## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
if (pres->get_DigitalSignatures()->get_Count() > 0)
{
    bool allSignaturesAreValid = true;

    System::Console::WriteLine(u"Signatures used to sign the presentation: ");

    for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
    {
        auto signature = pres->get_DigitalSignatures()->idx_get(i);
        System::Console::WriteLine(u"{0}, {1} --- {2}",
            signature->get_Certificate()->get_SubjectName()->get_Name(),
            signature->get_SignTime().ToString(u"yyyy-MM-dd HH:mm"),
            (signature->get_IsValid() ? u"VALID" : u"INVALID")
        );
        allSignaturesAreValid &= signature->get_IsValid();
    }
}
@verbatim 
if (allSignaturesAreValid)
    System::Console::WriteLine(u"Presentation is genuine, all signatures are valid.");
else
    System::Console::WriteLine(u"Presentation has been modified since signing.");
@endverbatim }
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDigitalSignatureCollection](../../idigitalsignaturecollection/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)