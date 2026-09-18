---
title: apply_default_paragraph_indents_shifts method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Define deslocamentos padrão diferentes de zero para o Indent e MarginLeft efetivos do parágrafo quando bullets está habilitado (como PowerPoint faz ao habilitar marcadores/numerção de parágrafo). Se bullets estiver desabilitado, apenas redefina o Indent e MarginLeft do parágrafo (como PowerPoint faz ao desabilitar marcadores/numerção de parágrafo). Os deslocamentos de recuo são aplicados em relação ao contexto atual do bullet - IBulletFormat.Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos diferentes de zero são aplicados ao Indent e MarginLeft efetivos do parágrafo atual (fazendo com que os valores resultantes sejam valores locais).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Chamar este método não tem efeito e lança **System.InvalidOperationException** nos seguintes casos:<br/>            se o objeto formatado pai não for um parágrafo (por exemplo, chamar ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() lançará exceção);<br/>            ou se o parágrafo não foi adicionado a nenhuma coleção ITextFrame.Paragraphs (adicione-o primeiro); |



### Veja Também
* classe [`BulletFormat`](/slides/python-net/pt/aspose.slides/bulletformat)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)