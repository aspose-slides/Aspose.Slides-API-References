---
title: get_SignTime()
second_title: Aspose.Slides для справочника API C++
description: "Время, когда документ был подписан. Только для чтения System::DateTime."
type: docs
weight: 27
url: /ru/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() метод


Время, когда документ был подписан. Только для чтения [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## См. также

* Класс [DateTime](../../../system/datetime/)
* Класс [IDigitalSignature](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)