---
title: get_Persistence()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Získá metodu používanou k ukládání vlastností ovládacího prvku ActiveX. Pouze pro čtení PersistenceType.
type: docs
weight: 1
url: /cs/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() metoda

Získá metodu používanou k ukládání vlastností ActiveX ovládacího prvku. Pouze pro čtení [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Poznámky

Následující příklad ukazuje použití vlastnosti Persistence pro kontrolu, zda mohou být vlastnosti objektu ActiveX změněny jako XML-založené vlastnosti ActiveX:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Použijte vlastní metodu pro správu vlastností ActiveX uložených v binárním souboru
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Viz také

* Výčet [PersistenceType](../../persistencetype/)
* Třída [Control](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)