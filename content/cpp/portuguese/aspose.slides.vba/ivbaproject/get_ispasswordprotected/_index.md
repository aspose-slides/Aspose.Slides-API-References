---
title: get_IsPasswordProtected()
second_title: Referência da API Aspose.Slides para C++
description: Indica se o VBAProject está protegido por uma senha para visualizar as propriedades do projeto. Somente leitura bool.
type: docs
weight: 40
url: /pt/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() método


Indica se o VBAProject está protegido por uma senha para visualizar as propriedades do projeto. Somente leitura **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Ver também

* Classe [IVbaProject](../)
* Espaço de nomes [Aspose::Slides::Vba](../../)
* Biblioteca [Aspose.Slides](../../../)