---
title: get_ActiveXControlBinary()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la persistencia de un control ActiveX cuando el método utilizado para persistir es PersistStream, PersistStreamInit o PersistStorage.
type: docs
weight: 118
url: /es/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() método

Especifica la persistencia de un control ActiveX cuando el método utilizado para persistir es PersistStream, PersistStreamInit o PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Observaciones

El siguiente ejemplo muestra el uso de la propiedad ActiveXControlBinary para cambiar propiedades de ActiveX:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Utilice su propio método para gestionar las propiedades ActiveX almacenadas en su archivo binario
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Control](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)