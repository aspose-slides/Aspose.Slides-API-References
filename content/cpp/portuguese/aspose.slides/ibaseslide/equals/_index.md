---
title: Equals()
second_title: Referência da API Aspose.Slides para C++
description: Determina se as duas instâncias IBaseSlide são iguais. O valor retornado é calculado com base na estrutura do slide e no conteúdo estático. Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId e conteúdo dinâmico, por exemplo o valor da data atual em Date Placeholder.
type: docs
weight: 183
url: /pt/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) método

Determina se as duas instâncias [IBaseSlide](../) são iguais. O valor retornado é calculado com base na estrutura do slide e no conteúdo estático. Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., são iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual em Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | O [IBaseSlide](../) a ser comparado com o [IBaseSlide](../) atual. |

### Valor de Retorno

**true** se o [IBaseSlide](../) especificado for igual ao [IBaseSlide](../) atual; caso contrário, **false**.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBaseSlide](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)