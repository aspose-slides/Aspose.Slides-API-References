---
title: get_IsValid()
second_title: Aspose.Slides для C++ справочник API
description: Если эта цифровая подпись действительна и документ не был изменён, это значение будет true. Только для чтения bool.
type: docs
weight: 14
url: /ru/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() метод

Если эта цифровая подпись действительна и документ не был изменён, это значение будет true. Только для чтения **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
```

## Примечания

```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## См. также

* Класс [IDigitalSignature](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)