---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides C++ API referencia
description: Megadja egy ActiveX vezérlő megőrzésének módját, amikor a megőrzéshez használt módszer a PersistStream, a PersistStreamInit vagy a PersistStorage.
type: docs
weight: 118
url: /hu/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() metódus

Megadja egy ActiveX vezérlő megőrzését, amikor a megőrzéshez használt módszer vagy a PersistStream, PersistStreamInit vagy a PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Megjegyzések

A következő példa bemutatja az ActiveXControlBinary tulajdonság használatát az ActiveX tulajdonságok módosításához:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Használja saját módszerét az ActiveX tulajdonságok bináris fájlban tárolt kezeléséhez
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Control](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)