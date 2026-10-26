---
title: get_Password()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém a senha. Leia System::String."
type: docs
weight: 105
url: /pt/aspose.slides/loadoptions/get_password/
---
## LoadOptions::get_Password() método

Obtém a senha. Leia [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_Password() override
```

## Observações

A senha. 

O código de exemplo a seguir mostra como abrir um PowerPoint protegido por senha [Presentation](../../presentation/). 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_Password(u"YOUR_PASSWORD");
auto presentation = System::MakeObject<Presentation>(u"pres.pptx", loadOptions);
// work with decrypted presentation
```

## Ver também

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)