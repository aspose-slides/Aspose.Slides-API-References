---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Referência da API Aspose.Slides para C++
description: "Define deslocamentos padrão diferentes de zero para o Indent e MarginLeft efetivos do parágrafo quando bullets está ativado (como o PowerPoint faz ao habilitar bullets/numeração de parágrafo). Se bullets estiver desativado, apenas redefine o Indent e MarginLeft do parágrafo (como o PowerPoint faz ao desativar bullets/numeração de parágrafo). Os deslocamentos de recuo são aplicados em relação ao contexto atual do bullet - IBulletFormat::get(set)_Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos de recuo diferentes de zero são aplicados ao Indent e MarginLeft efetivos do parágrafo atual (fazendo com que os valores resultantes sejam valores locais)."
type: docs
weight: 235
url: /pt/aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---
## BulletFormat::ApplyDefaultParagraphIndentsShifts() método

Define deslocamentos padrão diferentes de zero para o recuo (Indent) e margem esquerda (MarginLeft) efetivos do parágrafo quando bullets está habilitado (como PowerPoint faz ao habilitar bullets/numeração de parágrafo). Se bullets estiver desabilitado, apenas redefina o recuo (Indent) e a margem esquerda (MarginLeft) do parágrafo (como PowerPoint faz ao desabilitar bullets/numeração de parágrafo). Os deslocamentos de recuo são aplicados em relação ao contexto atual do bullet – IBulletFormat::get(set)_Type, .NumberedBulletStyle e FontHeight da primeira porção. Deslocamentos de recuo diferentes de zero são aplicados ao recuo (Indent) e à margem esquerda (MarginLeft) efetivos do parágrafo atual (fazendo com que os valores resultantes sejam valores locais).

```cpp
void Aspose::Slides::BulletFormat::ApplyDefaultParagraphIndentsShifts() override
```

## Veja Também

* Classe [BulletFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)