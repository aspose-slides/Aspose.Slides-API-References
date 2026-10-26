---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides для C++ справочник API
description: Указывает сохранность ActiveX-контрола, когда используемый метод сохранения — это PersistStream, PersistStreamInit или PersistStorage.
type: docs
weight: 118
url: /ru/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() метод

Указывает сохранность ActiveX-контрола, когда метод сохранения является PersistStream, PersistStreamInit или PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Примечания

Следующий пример демонстрирует использование свойства ActiveXControlBinary для изменения свойств ActiveX:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Используйте свой метод для управления свойствами ActiveX, хранящимися в его бинарном файле
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Control](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)