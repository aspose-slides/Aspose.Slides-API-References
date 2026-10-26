---
title: get_SignTime()
second_title: Referência da API Aspose.Slides para C++
description: "O horário em que o documento foi assinado. Somente leitura System::DateTime."
type: docs
weight: 27
url: /pt/aspose.slides/digitalsignature/get_signtime/
---
## DigitalSignature::get_SignTime() método


O horário em que o documento foi assinado. Somente leitura [System::DateTime](../../../system/datetime/).

```cpp
System::DateTime Aspose::Slides::DigitalSignature::get_SignTime() override
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");
for (int i = 0; i < pres->get_DigitalSignatures()->get_Count(); ++i)
{
    auto signature = pres->get_DigitalSignatures()->idx_get(i);
    System::Console::WriteLine(u"Signature check: {0}, Signing time: {1}",
        (signature->get_IsValid() ? u"VALID" : u"INVALID"),
        signature->get_SignTime()
    );
}
```

## Veja também

* Classe [DateTime](../../../system/datetime/)
* Classe [DigitalSignature](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)