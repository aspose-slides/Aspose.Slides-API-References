---
title: set_Password()
second_title: Referência da API Aspose.Slides para C++
description: "Define a senha. Escreva System::String."
type: docs
weight: 118
url: /pt/aspose.slides/loadoptions/set_password/
---
## LoadOptions::set_Password(System::String) método


Define a senha. Escreva [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_Password(System::String value) override
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

## Veja Também

* Classe [String](../../../system/string/)
* Classe [LoadOptions](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)