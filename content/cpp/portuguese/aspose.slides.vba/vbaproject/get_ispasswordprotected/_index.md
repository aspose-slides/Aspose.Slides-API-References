---
title: get_IsPasswordProtected()
second_title: Referência da API Aspose.Slides para C++
description: Indica se o VBAProject está protegido por uma senha para visualizar as propriedades do projeto. Somente leitura bool.
type: docs
weight: 40
url: /pt/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() método


Indica se o VBAProject está protegido por senha para visualizar as propriedades do projeto. Somente leitura **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Observações



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Veja também

* Classe [VbaProject](../)
* Namespace [Aspose::Slides::Vba](../../)
* Biblioteca [Aspose.Slides](../../../)