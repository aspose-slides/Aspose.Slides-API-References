---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica a persistência de um controle ActiveX quando o método usado para persistir é PersistStream, PersistStreamInit ou PersistStorage.
type: docs
weight: 118
url: /pt/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() método


Especifica a persistência de um controle ActiveX quando o método usado para persistir é PersistStream, PersistStreamInit ou PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Observações


O próximo exemplo mostra o uso da propriedade ActiveXControlBinary para alterar propriedades ActiveX: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Use seu próprio método para gerenciar propriedades ActiveX armazenadas no seu arquivo binário
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Control](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)