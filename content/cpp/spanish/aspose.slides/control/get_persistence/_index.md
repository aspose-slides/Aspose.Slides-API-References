---
title: get_Persistence()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el método utilizado para almacenar las propiedades del control ActiveX. Solo lectura PersistenceType.
type: docs
weight: 1
url: /es/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() método


Obtiene el método utilizado para almacenar las propiedades del control ActiveX. Solo lectura [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Observaciones


El siguiente ejemplo muestra el uso de la propiedad Persistence para comprobar si las propiedades del objeto ActiveX pueden ser modificadas como propiedades ActiveX basadas en XML:
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

* Enumeración [PersistenceType](../../persistencetype/)
* Clase [Control](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)