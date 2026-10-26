---
title: GetEffective()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém as propriedades de formatação de coluna de tabela efetivas com herança e estilos de tabela aplicados.
type: docs
weight: 1
url: /pt/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() método

Obtém as propriedades de formatação de coluna de tabela efetiva com herança e estilos de tabela aplicados.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### Valor de Retorno

Um [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## Observações

Este exemplo demonstra a obtenção do formato de preenchimento efetivo para diferentes partes lógicas da tabela. Observe que a formatação de célula sempre tem prioridade superior à formatação de linha, linha - superior à coluna, coluna - superior à tabela inteira. Portanto, finalmente as propriedades CellFormatEffectiveData são sempre usadas para desenhar a tabela. O código a seguir é apenas um exemplo da API. 
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
* Classe [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Classe [ColumnFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)