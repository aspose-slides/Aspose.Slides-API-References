---
title: get_GridSpacing()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Leitura float.
type: docs
weight: 92
url: /pt/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() método

Retorna o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Leitura **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Observações

O valor de espaçamento da grade deve ser um número positivo . O intervalo típico varia de 1 mm (2.8349607 pontos) a 2 polegadas (144 pontos). 

O código de exemplo a seguir mostra como alterar o espaçamento da grade em uma apresentação do PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Classe [ViewProperties](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)