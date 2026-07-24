---
title: AddTable()
second_title: C++ için Aspose.Slides API Referansı
description: Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 469
url: /tr/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metot


Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Tablonun x koordinatı, puan cinsinden. |
| y | **float** | Tablonun y koordinatı, puan cinsinden. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablo sütunlarının genişliklerini temsil eden double dizisi, puan cinsinden. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablo satırlarının yüksekliğini temsil eden double dizisi, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [ITable](../../itable/).

## Açıklamalar



Aşağıdaki örnekler, PowerPoint [Presentation](../../presentation/) içinde tablo eklemenin nasıl yapılacağını gösterir. 
```cpp
// PPTX dosyasını temsil eden Presentation sınıfının bir örneğini oluşturun
auto pres = System::MakeObject<Presentation>();
// İlk slayta erişin
auto slide = pres->get_Slides()->idx_get(0);
// Sütunları genişlikleriyle ve satırları yükseklikleriyle tanımlayın
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Slayta tablo şekli ekleyin
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Her hücre için kenarlık biçimini ayarlayın
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

// 1. satırın 1 ve 2. hücrelerini birleştirin
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Birleştirilmiş hücreye metin ekleyin
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// PPTX dosyasını diske kaydedin
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)