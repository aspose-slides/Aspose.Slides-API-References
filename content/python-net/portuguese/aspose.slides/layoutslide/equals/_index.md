---
title: equals method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/layoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina se as duas instâncias de IBaseSlide são iguais.
            O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.
            Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., são iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual em um Placeholder de Data.

### Retorno

**true**  se o IBaseSlide especificado for igual ao IBaseSlide atual; 
            caso contrário, **false** .


```python
def equals(self, slide):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide) | O IBaseSlide a ser comparado com o IBaseSlide atual. |


### Ver também
* classe [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide)
* classe [`LayoutSlide`](/slides/python-net/pt/aspose.slides/layoutslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)