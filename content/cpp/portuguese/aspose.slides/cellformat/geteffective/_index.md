---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém as propriedades de formatação de célula de tabela efetiva com herança e estilos de tabela aplicados.
type: docs
weight: 118
url: /pt/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() método

Obtém as propriedades de formatação de célula de tabela efetivas com herança e estilos de tabela aplicados.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### Valor de Retorno

Um [ICellFormatEffectiveData](../../icellformateffectivedata/).

## Observações

Este exemplo demonstra como obter o formato de preenchimento efetivo para diferentes partes lógicas da tabela. Observe que a formatação de células sempre tem prioridade maior que a formatação de linhas, linhas têm prioridade maior que colunas, colunas têm prioridade maior que a tabela inteira. Portanto, as propriedades CellFormatEffectiveData são sempre usadas para desenhar a tabela. O código a seguir é apenas um exemplo de API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Saída e comparação
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Classe [CellFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)