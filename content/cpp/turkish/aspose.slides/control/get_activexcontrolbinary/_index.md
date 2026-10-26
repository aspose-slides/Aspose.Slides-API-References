---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides için C++ API Referansı
description: Bir ActiveX denetiminin kalıcılığını, kalıcılığı sağlayan yöntem PersistStream, PersistStreamInit veya PersistStorage olduğunda belirler.
type: docs
weight: 118
url: /tr/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() yöntemi

Bir ActiveX denetiminin kalıcılığını, kalıcılığı sağlamak için kullanılan yöntem PersistStream, PersistStreamInit veya PersistStorage olduğunda belirtir.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Açıklamalar

Sonraki örnek, ActiveX özelliklerini değiştirmek için ActiveXControlBinary özelliğinin kullanımını gösterir:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // İkili dosyasında depolanan ActiveX özelliklerini yönetmek için kendi yönteminizi kullanın
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Bkz

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Control](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)