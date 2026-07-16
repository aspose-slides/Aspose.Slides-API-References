---
title: Remove()
second_title: Référence API Aspose.Slides pour C++
description: Supprime la première occurrence d'un objet spécifique de la collection/>
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) méthode


Supprime la première occurrence d'un objet spécifique de la collection/>. 

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | L'objet à supprimer de la collection. |

### Valeur de retour

true si *mathBlock* a été supprimé avec succès de la collection ; sinon, false. Cette méthode renvoie également false si *mathBlock* n'est pas trouvé dans la collection originale/>.
## Remarques



Exemple: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)