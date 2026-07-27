---
title: get_GridSpacing()
second_title: Aspose.Slides para Referência da API C++
description: Retorna o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Ler **float**.
type: docs
weight: 92
url: /pt/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() method

Retorna o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Ler **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Observações

O valor do espaçamento da grade deve ser um número positivo. A faixa típica de valores vai de 1 mm (2.8349607 pontos) a 2 polegadas (144 pontos).

O código de exemplo a seguir mostra como alterar o espaçamento da grade em uma apresentação do PowerPoint.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Classe [IViewProperties](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)