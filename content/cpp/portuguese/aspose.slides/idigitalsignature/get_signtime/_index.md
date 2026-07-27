---
title: get_SignTime()
second_title: Aspose.Slides para C++ Referência da API
description: "O horário em que o documento foi assinado. Somente leitura System::DateTime."
type: docs
weight: 27
url: /pt/aspose.slides/idigitalsignature/get_signtime/
---
## IDigitalSignature::get_SignTime() método


O horário em que o documento foi assinado. Somente leitura [System::DateTime](../../../system/datetime/).

```cpp
virtual System::DateTime Aspose::Slides::IDigitalSignature::get_SignTime()=0
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(System::String(u"Signature check: ") + (signature->get_IsValid() ? u"VALID" : u"INVALID") + u", Signing time: " + signature->get_SignTime());
}
```

## Veja também

* Classe [DateTime](../../../system/datetime/)
* Classe [IDigitalSignature](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)