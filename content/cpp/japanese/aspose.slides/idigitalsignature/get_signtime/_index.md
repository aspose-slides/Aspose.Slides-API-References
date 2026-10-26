---
title: get_SignTime()
second_title: Aspose.Slides for C++ API リファレンス
description: "ドキュメントが署名された時刻です。読み取り専用 System::DateTime."
type: docs
weight: 27
url: /ja/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() メソッド


ドキュメントが署名された時刻。読み取り専用 [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## 備考



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## 参照

* クラス [DateTime](../../../system/datetime/)
* クラス [IDigitalSignature](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)