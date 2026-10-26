---
title: AddTable()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouveau tableau et l'ajoute à la fin de la collection de formes.
type: docs
weight: 469
url: /fr/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) méthode

Crée un nouveau tableau et l’ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du tableau, en points. |
| y | **float** | La coordonnée y du tableau, en points. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un tableau de doubles représentant les largeurs des colonnes du tableau, en points. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Un tableau de doubles représentant les hauteurs des lignes du tableau, en points. |

### Valeur de retour

Le [ITable](../../itable/) nouvellement créé.

## Remarques

L'exemple suivant montre comment ajouter un tableau dans PowerPoint [Presentation](../../presentation/).
```cpp
// Instancie la classe Presentation qui représente le fichier PPTX
auto pres = System::MakeObject<Presentation>();
// Accède à la première diapositive
auto slide = pres->get_Slides()->idx_get(0);
// Définit les colonnes avec leurs largeurs et les lignes avec leurs hauteurs
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Ajoute la forme de tableau à la diapositive
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Définit le format des bordures pour chaque cellule
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

// Fusionne les cellules 1 et 2 de la ligne 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Ajoute du texte à la cellule fusionnée
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Enregistre le PPTX sur le disque
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ITable](../../itable/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)