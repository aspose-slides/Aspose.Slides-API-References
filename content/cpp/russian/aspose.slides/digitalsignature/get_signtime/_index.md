---
title: get_SignTime()
second_title: Справочник API Aspose.Slides для C++
description: "Время, когда документ был подписан. Только для чтения System::DateTime."
type: docs
weight: 27
url: /ru/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() метод


Время, когда документ был подписан. Только для чтения [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Примечания



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

## См. также

* Класс [DateTime](../../../system/datetime/)
* Класс [DigitalSignature](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)