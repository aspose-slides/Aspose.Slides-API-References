---
title: get_ReadOnlyRecommended()
second_title: Справочник API Aspose.Slides для C++
description: Получает рекомендацию только для чтения. Чтение bool.
type: docs
weight: 79
url: /ru/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() method


Получает рекомендацию только для чтения. Чтение **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
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