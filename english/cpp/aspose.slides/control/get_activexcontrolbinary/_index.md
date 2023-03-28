---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage.
type: docs
weight: 118
url: /cpp/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() method


Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Remarks


Next example shows the using ActiveXControlBinary property for changing ActiveX properties: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Use your own method for managing ActiveX properties stored in its binary file
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Control](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
