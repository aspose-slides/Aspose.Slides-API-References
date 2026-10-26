---
title: get_Persistence()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il metodo utilizzato per memorizzare le proprietà del controllo ActiveX. Solo lettura PersistenceType.
type: docs
weight: 1
url: /it/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() metodo

Restituisce il metodo usato per memorizzare le proprietà del controllo ActiveX. Solo lettura [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Osservazioni

Il prossimo esempio mostra l'uso della proprietà Persistence per verificare se le proprietà dell'oggetto ActiveX possono essere modificate come proprietà ActiveX basate su XML:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Usa il tuo metodo per gestire le proprietà ActiveX memorizzate nel suo file binario
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Vedi anche

* Enum [PersistenceType](../../persistencetype/)
* Classe [Control](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)