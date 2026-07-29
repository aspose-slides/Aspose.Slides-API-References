---
title: get_Persistence()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar metoden som används för att lagra egenskaperna för ActiveX-kontrollen. Skrivskyddad PersistenceType.
type: docs
weight: 1
url: /sv/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() metod


Hämtar metoden som används för att lagra egenskaperna för ActiveX-kontrollen. Skrivskyddad [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Anmärkningar


Nästa exempel visar hur Persistence-egenskapen används för att kontrollera om egenskaperna för ActiveX-objektet kan ändras som XML-baserade ActiveX-egenskaper: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Använd din egen metod för att hantera ActiveX-egenskaper lagrade i dess binära fil
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Se även

* Enum [PersistenceType](../../persistencetype/)
* Klass [Control](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)