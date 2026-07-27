---
title: get_IsValid()
second_title: Referência da API Aspose.Slides para C++
description: Se esta assinatura digital for válida e o documento não tiver sido adulterado, este valor será verdadeiro. Somente leitura bool.
type: docs
weight: 14
url: /pt/aspose.slides/digitalsignature/get_isvalid/
---
## DigitalSignature::get_IsValid() método


Se esta assinatura digital for válida e o documento não tiver sido adulterado, este valor será verdadeiro. Somente leitura **bool**.

```cpp
bool Aspose::Slides::DigitalSignature::get_IsValid() override
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID"));
}
```

## Ver também

* Classe [DigitalSignature](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)