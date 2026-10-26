---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides для справочника API C++
description: Получает рекомендацию о режиме только для чтения. Возвращаемый тип bool.
type: docs
weight: 79
url: /ru/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() метод


Получает рекомендацию о режиме только для чтения. Возвращаемый тип **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
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
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)