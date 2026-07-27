---
title: AddTable()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova tabela e a adiciona ao final da coleção de formas.
type: docs
weight: 469
url: /pt/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method

Cria uma nova tabela e a adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A coordenada x da tabela, em pontos. |
| y | **float** | A coordenada y da tabela, em pontos. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Um array de doubles representando as larguras das colunas da tabela, em pontos. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Um array de doubles representando as alturas das linhas da tabela, em pontos. |

### Valor de Retorno

O [ITable](../../itable/) recém-criado.

## Observações

O exemplo a seguir mostra como adicionar uma tabela no PowerPoint [Presentation](../../presentation/). 
```cpp
// Instanciar a classe Presentation que representa um arquivo PPTX
auto pres = System::MakeObject<Presentation>();
// Acessar o primeiro slide
auto slide = pres->get_Slides()->idx_get(0);
// Definir colunas com larguras e linhas com alturas
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Adicionar forma de tabela ao slide
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Definir o formato da borda para cada célula
for (int32_t row = 0; row < table->get_Rows()->get_Count(); row++)
{
    auto currentRow = table->get_Rows()->idx_get(row);
    for (int32_t col = 0; col < currentRow->get_Count(); col++)
    {
        auto cell = currentRow->idx_get(col);
        auto cellFormat = cell->get_CellFormat();
        cellFormat->get_BorderTop()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderTop()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderTop()->set_Width(5);
        cellFormat->get_BorderBottom()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderBottom()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderBottom()->set_Width(5);
        cellFormat->get_BorderLeft()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderLeft()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderLeft()->set_Width(5);
        cellFormat->get_BorderRight()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderRight()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderRight()->set_Width(5);
    }
}

// Mesclar as células 1 e 2 da linha 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Adicionar texto à célula mesclada
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Salvar o PPTX no disco
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ITable](../../itable/)
* Classe [ShapeCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)