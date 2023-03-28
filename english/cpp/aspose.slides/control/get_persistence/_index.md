---
title: get_Persistence()
second_title: Aspose.Slides for C++ API Reference
description: Gets the method used to store properties of the ActiveX control. Read only PersistenceType.
type: docs
weight: 1
url: /cpp/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() method


Gets the method used to store properties of the ActiveX control. Read only [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Remarks


Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties: 
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

* Enum [PersistenceType](../../persistencetype/)
* Class [Control](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
