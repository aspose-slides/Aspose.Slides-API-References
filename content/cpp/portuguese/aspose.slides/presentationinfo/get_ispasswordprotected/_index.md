---
title: get_IsPasswordProtected()
second_title: Referência da API Aspose.Slides para C++
description: Obtém um valor que indica se uma apresentação vinculada está protegida por uma senha para abrir.
type: docs
weight: 14
url: /pt/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() método


Obtém um valor que indica se uma apresentação vinculada está protegida por uma senha para abrir.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Observações



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Veja Também

* Classe [PresentationInfo](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)