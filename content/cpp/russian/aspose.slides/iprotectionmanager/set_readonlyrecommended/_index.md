---
title: set_ReadOnlyRecommended()
second_title: Справочная документация API Aspose.Slides для C++
description: Устанавливает рекомендацию только для чтения. Записывает **bool**.
type: docs
weight: 92
url: /ru/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) метод


Устанавливает рекомендацию только для чтения. Записывает **bool**.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [IProtectionManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)