---
title: show_category_name property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name propriedade
Representa o comportamento de exibição do nome da categoria do rótulo de dados de um gráfico especificado.
            True para exibir o nome da categoria dos rótulos de dados em um gráfico. False para ocultar.
            Leitura/gravação **bool**.


### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade ShowCategoryName para os novos rótulos de dados na coleção DataLabelCollection.
            Definir esta propriedade com um valor também define esse valor na propriedade ShowCategoryName para todos os rótulos de dados na coleção DataLabelCollection
            (por exemplo, "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" faz com que todos DataLabels[i].ShowCategoryName sejam iguais a val).

### Definição:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### Veja Também
* classe [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)