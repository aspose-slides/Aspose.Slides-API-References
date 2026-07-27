---
title: get_IsWriteProtected()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém um valor que indica se uma apresentação vinculada está protegida contra gravação.
type: docs
weight: 27
url: /pt/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() método


Obtém um valor que indica se uma apresentação vinculada está protegida contra gravação.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Observações



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Se a apresentação estiver protegida por uma senha para abertura, o valor da propriedade é igual a NotDefined. Veja [NullableBool](../../nullablebool/) enumeração. 
## Veja Também

* Enum [NullableBool](../../nullablebool/)
* Classe [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)