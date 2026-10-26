---
title: get_Password()
second_title: Aspose.Slides для C++ справочник API
description: "Получает пароль. Читайте System::String."
type: docs
weight: 105
url: /ru/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() метод

Получает пароль. Читайте [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Примечания

Пароль.

Следующий пример кода показывает, как открыть защищённый паролем PowerPoint [Presentation](../../presentation/).
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [LoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)