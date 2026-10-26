---
title: set_GridSpacing()
second_title: Referência da API Aspose.Slides para C++
description: Define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Escreva float.
type: docs
weight: 105
url: /pt/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) método

Define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Escreva **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Observações

O valor do espaçamento da grade deve ser um número positivo. O intervalo típico de valores vai de 1 mm (2.8349607 pontos) a 2 polegadas (144 pontos).

O código de exemplo a seguir mostra como alterar o espaçamento da grade em uma apresentação do PowerPoint.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Ver também

* Classe [ViewProperties](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)