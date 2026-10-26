---
title: SplitTextByColumns()
second_title: Référence de l'API Aspose.Slides pour C++
description: Divise le contenu texte du ITextFrame en un tableau de chaînes, où chaque élément correspond à une colonne de texte distincte dans le cadre.
type: docs
weight: 118
url: /fr/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() méthode


Divise le contenu texte du [ITextFrame](../) en un tableau de chaînes, 

 où chaque élément correspond à une colonne de texte distincte dans le cadre.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Valeur de retour

Un tableau de chaînes, où chaque chaîne représente le contenu texte d'une colonne spécifique dans le [ITextFrame](../).
## Remarques



Si le cadre de texte ne contient pas plusieurs colonnes, le tableau retourné comportera un seul élément contenant le texte complet. 

 Les colonnes vides seront représentées comme des chaînes vides dans le tableau. 

L'exemple suivant montre comment utiliser [ITextFrame::SplitTextByColumns](./) : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Obtenir la première forme sur la diapositive et la convertir en ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Diviser le contenu du cadre de texte en colonnes
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Afficher le texte de chaque colonne dans la console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)