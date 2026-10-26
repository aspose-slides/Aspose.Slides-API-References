---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides для справочника API C++
description: Устанавливает рекомендацию только для чтения. Запишите bool.
type: docs
weight: 92
url: /ru/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) метод


Устанавливает рекомендацию только для чтения. Запишите **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Примечания


Следующий пример кода показывает, как установить PowerPoint [Presentation](../../presentation/) в режим только для чтения в C# с использованием [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [ProtectionManager](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)