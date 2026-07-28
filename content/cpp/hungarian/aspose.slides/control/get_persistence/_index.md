---
title: get_Persistence()
second_title: Aspose.Slides C++ API-referencia
description: Megkapja a módszert, amelyet az ActiveX vezérlő tulajdonságainak tárolására használnak. Csak olvasható PersistenceType.
type: docs
weight: 1
url: /hu/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() metódus


Megkapja a módszert, amelyet az ActiveX vezérlő tulajdonságainak tárolására használnak. Csak olvasható [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Megjegyzések


A következő példa bemutatja a Persistence tulajdonság használatát annak ellenőrzésére, hogy az ActiveX objektum tulajdonságai XML-alapú ActiveX tulajdonságokként módosíthatók-e: 
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

* Enum [PersistenceType](../../persistencetype/)
* Osztály [Control](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)