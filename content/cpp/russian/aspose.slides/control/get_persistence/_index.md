---
title: get_Persistence()
second_title: Aspose.Slides для справочника API C++
description: Получает метод, используемый для хранения свойств ActiveX-контрола. Только для чтения PersistenceType.
type: docs
weight: 1
url: /ru/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() метод

Получает метод, используемый для хранения свойств ActiveX-контрола. Только для чтения [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Примечания

Следующий пример показывает, как использовать свойство Persistence для проверки того, могут ли свойства объекта ActiveX изменяться как свойства ActiveX на основе XML: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Используйте ваш собственный метод для управления свойствами ActiveX, хранящимися в его бинарном файле
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## См. также

* Enum [PersistenceType](../../persistencetype/)
* Class [Control](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)