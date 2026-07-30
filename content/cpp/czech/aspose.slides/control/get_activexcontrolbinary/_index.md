---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides pro C++ referenci API
description: Určuje trvalost ActiveX ovládacího prvku, pokud je metoda používaná k uložení buď PersistStream, PersistStreamInit nebo PersistStorage.
type: docs
weight: 118
url: /cs/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() metoda

Určuje trvalost ActiveX ovládacího prvku, pokud je metoda použitá k uložení buď PersistStream, PersistStreamInit nebo PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Poznámky

Následující příklad ukazuje použití vlastnosti ActiveXControlBinary pro změnu vlastností ActiveX: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Použijte vlastní metodu pro správu ActiveX vlastností uložených v jeho binárním souboru
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Control](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)