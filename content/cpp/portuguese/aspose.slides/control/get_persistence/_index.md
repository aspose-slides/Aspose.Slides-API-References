---
title: get_Persistence()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém o método usado para armazenar propriedades do controle ActiveX. Somente leitura PersistenceType.
type: docs
weight: 1
url: /pt/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() método

Obtém o método usado para armazenar propriedades do controle ActiveX. Somente leitura [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Observações

O próximo exemplo mostra o uso da propriedade Persistence para verificar se as propriedades do objeto ActiveX podem ser alteradas como propriedades ActiveX baseadas em XML:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Use seu próprio método para gerenciar as propriedades ActiveX armazenadas em seu arquivo binário
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Veja Também

* Enum [PersistenceType](../../persistencetype/)
* Classe [Control](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)