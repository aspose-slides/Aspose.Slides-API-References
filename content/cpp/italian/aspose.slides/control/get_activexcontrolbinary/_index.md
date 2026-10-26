---
title: get_ActiveXControlBinary()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la persistenza di un controllo ActiveX quando il metodo utilizzato per persistere è PersistStream, PersistStreamInit o PersistStorage.
type: docs
weight: 118
url: /it/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() metodo

Specifica la persistenza di un controllo ActiveX quando il metodo utilizzato per persistere è PersistStream, PersistStreamInit o PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Osservazioni

Il prossimo esempio mostra l'uso della proprietà ActiveXControlBinary per modificare le proprietà ActiveX: 
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

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Control](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)