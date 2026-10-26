---
title: get_Persistence()
second_title: Aspose.Slides C++ için API Referansı
description: ActiveX denetiminin özelliklerini depolamak için kullanılan yöntemi alır. Yalnızca okunur PersistenceType.
type: docs
weight: 1
url: /tr/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() yöntemi

ActiveX denetiminin özelliklerini depolamak için kullanılan yöntemi alır. Yalnızca okunur [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Açıklamalar

Aşağıdaki örnek, Persistence özelliğinin kullanımını, ActiveX nesnesinin özelliklerinin XML tabanlı ActiveX özellikleri olarak değiştirilebilir olup olmadığını kontrol etmek için gösterir: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Kendi yönteminizle ikili dosyada depolanan ActiveX özelliklerini yönetin
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Ayrıca Bakınız

* Enum [PersistenceType](../../persistencetype/)
* Class [Control](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)