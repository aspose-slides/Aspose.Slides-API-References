---
title: set_Password()
second_title: Aspose.Slides для C++ API Reference
description: "Устанавливает пароль. Запишите System::String."
type: docs
weight: 118
url: /ru/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) метод


Устанавливает пароль. Запишите [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
```

## Замечания


Пароль. 

Следующий пример кода показывает, как открыть защищённую паролем презентацию PowerPoint [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## См. также

* Класс [String](../../../system/string/)
* Класс [LoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)