---
title: Encrypt()
second_title: Aspose.Slides для C++ справочник API
description: Шифрует презентацию с указанным паролем.
type: docs
weight: 105
url: /ru/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) метод

Шифрует [Presentation](../../presentation/) с указанным паролем.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | Пароль. |
## Примечания

Следующий пример кода показывает, как зашифровать PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [String](../../../system/string/)
* Класс [ProtectionManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)