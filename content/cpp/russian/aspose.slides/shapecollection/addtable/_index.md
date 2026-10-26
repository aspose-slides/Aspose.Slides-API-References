---
title: AddTable()
second_title: Справочник API Aspose.Slides для C++
description: Создает новую таблицу и добавляет её в конец коллекции фигур.
type: docs
weight: 469
url: /ru/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Создает новую таблицу и добавляет её в конец коллекции фигур.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x таблицы в пунктах. |
| y | **float** | Координата y таблицы в пунктах. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Массив значений **double**, представляющих ширину столбцов таблицы, в пунктах. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Массив значений **double**, представляющих высоту строк таблицы, в пунктах. |

### Возвращаемое значение

Ново созданный [ITable](../../itable/).
## Замечания



В следующих примерах показано, как добавить таблицу в PowerPoint [Presentation](../../presentation/). 
```cpp
// Создать экземпляр класса Presentation, представляющего файл PPTX
auto pres = System::MakeObject<Presentation>();
// Получить первый слайд
auto slide = pres->get_Slides()->idx_get(0);
// Определить столбцы с ширинами и строки с высотами
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Добавить форму таблицы на слайд
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Установить формат границы для каждой ячейки
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

// Объединить ячейки 1 и 2 строки 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Добавить текст в объединённую ячейку
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Сохранить PPTX на диск
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)