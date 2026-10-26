---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os dados de plano de fundo efetivos com a herança aplicada.
type: docs
weight: 118
url: /pt/aspose.slides/background/geteffective/
---
## Background::GetEffective() método

Obtém os dados de plano de fundo efetivos com a herança aplicada.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```

### Valor de Retorno

Um [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).

## Observações

Este exemplo demonstra como obter propriedades de plano de fundo efetivas.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Classe [Background](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)