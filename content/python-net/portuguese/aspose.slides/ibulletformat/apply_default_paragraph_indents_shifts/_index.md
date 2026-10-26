---
title: apply_default_paragraph_indents_shifts method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Define os deslocamentos padrão diferentes de zero para o Indent e MarginLeft efetivo do parágrafo quando os marcadores estão habilitados (como o PowerPoint faz ao habilitar marcadores/numeração de parágrafo nele). Se os marcadores estiverem desabilitados, apenas redefina o Indent e MarginLeft do parágrafo (como o PowerPoint faz ao desabilitar marcadores/numeração de parágrafo nele). Os deslocamentos de indentação são aplicados em relação ao contexto atual do marcador – IBulletFormat.Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos diferentes de zero são aplicados ao Indent e MarginLeft efetivo do parágrafo atual (fazendo com que os valores resultantes sejam valores locais).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Chamar este método não tem efeito e lança **System.InvalidOperationException** nos seguintes casos:<br/>            se o objeto formatado pai não for um parágrafo (por exemplo, chamar ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() lançará exceção);<br/>            ou se o parágrafo não foi adicionado a nenhuma coleção ITextFrame.Paragraphs (adicione-o primeiro); |

### Ver também
* classe [`IBulletFormat`](/slides/python-net/pt/aspose.slides/ibulletformat)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)