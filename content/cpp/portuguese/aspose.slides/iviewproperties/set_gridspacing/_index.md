---
title: set_GridSpacing()
second_title: Aspose.Slides para C++ Referência da API
description: Define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Escreva float.
type: docs
weight: 105
url: /pt/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) método


Define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Escreva **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
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

* Classe [IViewProperties](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)