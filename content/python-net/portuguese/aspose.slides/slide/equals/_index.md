---
title: equals method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/slide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina se duas instâncias de IBaseSlide são iguais.
            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.
            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não leva em conta valores de identificadores únicos, como SlideId, e conteúdo dinâmico, como o valor da data atual em Placeholder de Data.

### Retorna

**true**  se o IBaseSlide especificado for igual ao IBaseSlide atual; 
            caso contrário, **false** .

```python
def equals(self, slide):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide) | O IBaseSlide a ser comparado com o IBaseSlide atual. |

### Veja Também
* classe [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide)
* classe [`Slide`](/slides/python-net/pt/aspose.slides/slide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)