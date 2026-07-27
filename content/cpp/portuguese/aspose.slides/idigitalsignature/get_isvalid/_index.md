---
title: get_IsValid()
second_title: Referência da API Aspose.Slides para C++
description: Se esta assinatura digital for válida e o documento não tiver sido adulterado, este valor será verdadeiro. Somente leitura bool.
type: docs
weight: 14
url: /pt/aspose.slides/idigitalsignature/get_isvalid/
---
## IDigitalSignature::get_IsValid() método


Se esta assinatura digital for válida e o documento não tiver sido adulterado, este valor será verdadeiro. Somente leitura **bool**.

```cpp
virtual bool Aspose::Slides::IDigitalSignature::get_IsValid()=0
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

* Classe [IDigitalSignature](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)