---
title: AddTable()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί έναν νέο πίνακα και τον προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 469
url: /el/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) μέθοδος

Δημιουργεί ένα νέο πίνακα και τον προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του πίνακα, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πίνακα, σε σημεία. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ένας πίνακας διπλών αριθμών που αντιπροσωπεύει τα πλάτη των στηλών του πίνακα, σε σημεία. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ένας πίνακας διπλών αριθμών που αντιπροσωπεύει τα ύψη των γραμμών του πίνακα, σε σημεία. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [ITable](../../itable/).

## Σχόλια

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε πίνακα στο PowerPoint [Presentation](../../presentation/). 
```cpp
// Δημιουργία αντικειμένου Presentation που αντιπροσωπεύει αρχείο PPTX
auto pres = System::MakeObject<Presentation>();
// Πρόσβαση στην πρώτη διαφάνεια
auto slide = pres->get_Slides()->idx_get(0);
// Ορισμός στηλών με πλάτη και γραμμών με ύψη
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Προσθήκη σχήματος πίνακα στη διαφάνεια
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Ορισμός μορφής περιγράμματος για κάθε κελί
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

// Συγχώνευση κελιών 1 & 2 της γραμμής 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Προσθήκη κειμένου στο συγχωνευμένο κελί
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Αποθήκευση PPTX στο δίσκο
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ITable](../../itable/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)