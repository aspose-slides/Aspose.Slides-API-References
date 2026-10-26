---
title: SplitTextByColumns()
second_title: Référence API Aspose.Slides pour C++
description: Divise le contenu texte du ITextFrame en un tableau de chaînes, où chaque élément correspond à une colonne de texte distincte dans le cadre.
type: docs
weight: 144
url: /fr/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() méthode


Divise le contenu texte du [ITextFrame](../../itextframe/) en un tableau de chaînes, 
 où chaque élément correspond à une colonne de texte distincte dans le cadre.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### Valeur retournée

Un tableau de chaînes, où chaque chaîne représente le contenu texte d'une colonne spécifique 
 dans le [ITextFrame](../../itextframe/).
## Remarques



Si le cadre de texte ne contient pas plusieurs colonnes, le tableau retourné contiendra un seul élément 
 contenant le texte complet. 
 Les colonnes vides seront représentées par des chaînes vides dans le tableau. 
L'exemple suivant montre comment utiliser [TextFrame::SplitTextByColumns](./) : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Get the first shape on the slide and cast it to ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Split the text frame content into columns
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Print each column's text to the console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [TextFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)