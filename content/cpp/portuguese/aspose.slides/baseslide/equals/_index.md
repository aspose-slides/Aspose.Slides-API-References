---
title: Equals()
second_title: Referência da API Aspose.Slides para C++
description: Determina se as duas instâncias IBaseSlide são iguais. O valor retornado é calculado com base na estrutura do slide e no conteúdo estático. Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual no Espaço Reservado de Data.
type: docs
weight: 170
url: /pt/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) método

Determina se as duas instâncias [IBaseSlide](../../ibaseslide/) são iguais. O valor retornado é calculado com base na estrutura do slide e no conteúdo estático. Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não leva em consideração valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual em Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | O [IBaseSlide](../../ibaseslide/) para comparar com o [IBaseSlide](../../ibaseslide/) atual. |

### Valor de retorno

**true** se o [IBaseSlide](../../ibaseslide/) especificado for igual ao [IBaseSlide](../../ibaseslide/) atual; caso contrário, **false**.

## Observações

O exemplo a seguir mostra como comparar dois slides. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBaseSlide](../../ibaseslide/)
* Classe [BaseSlide](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)