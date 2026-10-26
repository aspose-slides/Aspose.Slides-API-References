---
title: equals method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/masternotesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina se as duas instâncias de IBaseSlide são iguais.  
O valor retornado é calculado com base na estrutura do slide e no conteúdo estático.  
Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., são iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual em um Espaço Reservado de Data.

### Retorno

**true**  se o IBaseSlide especificado for igual ao IBaseSlide atual;  
caso contrário, **false** .


```python
def equals(self, slide):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide) | O IBaseSlide a comparar com o IBaseSlide atual. |

### Veja também
* classe [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide)
* classe [`MasterNotesSlide`](/slides/python-net/pt/aspose.slides/masternotesslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)