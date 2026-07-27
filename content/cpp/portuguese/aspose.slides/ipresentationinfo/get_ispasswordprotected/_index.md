---
title: get_IsPasswordProtected()
second_title: Referência da API Aspose.Slides para C++
description: Obtém um valor que indica se uma apresentação vinculada está protegida por senha para abrir.
type: docs
weight: 14
url: /pt/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() método

Obtém um valor que indica se uma apresentação vinculada está protegida por senha para abrir.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Observações



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Veja também

* Classe [IPresentationInfo](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)