---
title: get_Persistence()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Pobiera metodę używaną do przechowywania właściwości kontrolki ActiveX. Tylko do odczytu PersistenceType.
type: docs
weight: 1
url: /pl/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() metoda


Pobiera metodę używaną do przechowywania właściwości kontrolki ActiveX. Tylko do odczytu [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Uwagi


Poniższy przykład pokazuje użycie właściwości Persistence do sprawdzenia, czy właściwości obiektu ActiveX mogą być zmieniane jako właściwości ActiveX oparte na XML:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Użyj własnej metody do zarządzania właściwościami ActiveX przechowywanymi w jej pliku binarnym
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Zobacz także

* Enum [PersistenceType](../../persistencetype/)
* Class [Control](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)