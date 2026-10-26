---
title: equals method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina se as duas instâncias de IBaseSlide são iguais.
O valor retornado é calculado com base na estrutura e no conteúdo estático do slide.
Dois slides são iguais se todas as formas, estilos, textos, animação e outras configurações, etc., forem iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual no Marcador de data.

### Retorno

**true** se o IBaseSlide especificado for igual ao IBaseSlide atual; caso contrário, **false** .

```python
def equals(self, slide):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide) | O IBaseSlide a ser comparado com o IBaseSlide atual. |

### Ver também
* classe [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide)
* classe [`MasterHandoutSlide`](/slides/python-net/pt/aspose.slides/masterhandoutslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)