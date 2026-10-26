---
title: get_SignTime()
second_title: C++ 用 Aspose.Slides API リファレンス
description: "ドキュメントが署名された時間です。読み取り専用 System::DateTime."
type: docs
weight: 27
url: /ja/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() method


ドキュメントが署名された時間です。読み取り専用 [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## 備考



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

## 参照

* クラス [DateTime](../../../system/datetime/)
* クラス [DigitalSignature](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)