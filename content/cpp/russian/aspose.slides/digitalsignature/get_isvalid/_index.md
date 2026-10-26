---
title: get_IsValid()
second_title: Aspose.Slides для C++ справочник API
description: Если эта цифровая подпись действительна и документ не был изменён, это значение будет истинным. Только для чтения bool.
type: docs
weight: 14
url: /ru/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() метод


Если эта цифровая подпись действительна и документ не был изменён, это значение будет истинным. Только для чтения **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
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

* Класс [DigitalSignature](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)