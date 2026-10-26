---
title: get_IsWriteProtected()
second_title: Referência da API Aspose.Slides para C++
description: Obtém um valor que indica se uma apresentação vinculada está protegida contra gravação.
type: docs
weight: 27
url: /pt/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() método


Obtém um valor que indica se uma apresentação vinculada está protegida contra gravação.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Observações



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Se a apresentação estiver protegida por uma senha para abrir, o valor da propriedade é igual a NotDefined. 
## Veja Também

* Enum [NullableBool](../../nullablebool/)
* classe [PresentationInfo](../)
* namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)