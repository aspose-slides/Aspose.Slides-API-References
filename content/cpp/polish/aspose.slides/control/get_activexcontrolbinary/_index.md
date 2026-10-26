---
title: get_ActiveXControlBinary()
second_title: Referencja API Aspose.Slides dla C++
description: Określa trwałość kontrolki ActiveX, gdy metodą używaną do zachowania jest PersistStream, PersistStreamInit lub PersistStorage.
type: docs
weight: 118
url: /pl/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() metoda

Określa trwałość kontrolki ActiveX, gdy metodą używaną do zachowania jest PersistStream, PersistStreamInit lub PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Uwagi

Następny przykład pokazuje użycie właściwości ActiveXControlBinary do zmiany właściwości ActiveX:

```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Użyj własnej metody do zarządzania właściwościami ActiveX przechowywanymi w jej binarnym pliku
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [Control](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)