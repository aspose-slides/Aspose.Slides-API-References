---
title: get_IsValid()
second_title: Aspose.Slides for C++ API リファレンス
description: このデジタル署名が有効で、ドキュメントが改ざんされていない場合、この値は true になります。読み取り専用 bool.
type: docs
weight: 14
url: /ja/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() メソッド

このデジタル署名が有効で、ドキュメントが改ざんされていない場合、この値は true になります。読み取り専用 **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## 参照

* クラス [IDigitalSignature](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)