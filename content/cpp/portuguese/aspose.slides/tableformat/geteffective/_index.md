---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém as propriedades efetivas de formatação de tabela com herança e estilos de tabela aplicados.
type: docs
weight: 40
url: /pt/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() method


Obtém as propriedades efetivas de formatação de tabela com herança e estilos de tabela aplicados.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### Valor de Retorno

Um [ITableFormatEffectiveData](../../itableformateffectivedata/).
## Observações



Este exemplo demonstra a obtenção do formato de preenchimento efetivo para diferentes partes lógicas da tabela. Observe que a formatação de célula sempre tem prioridade maior que a formatação de linha, linha - maior que coluna, coluna - maior que a tabela inteira. Portanto, finalmente as propriedades CellFormatEffectiveData são sempre usadas para desenhar a tabela. O código a seguir é apenas um exemplo da API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Classe [TableFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)