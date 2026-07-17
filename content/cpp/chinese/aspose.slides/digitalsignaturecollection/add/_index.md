---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 在集合末尾添加签名。
type: docs
weight: 53
url: /zh/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) 方法

在集合末尾添加签名。

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | 要添加的签名。 |
## 备注



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDigitalSignature](../../idigitalsignature/)
* 类 [DigitalSignatureCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)