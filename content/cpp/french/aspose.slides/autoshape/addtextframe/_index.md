---
title: AddTextFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute un nouveau TextFrame à une forme. Si la forme possède déjà TextFrame alors il modifie simplement son texte.
type: docs
weight: 66
url: /fr/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) méthode


Ajoute un nouveau [TextFrame](../../textframe/) à une forme. Si la forme possède déjà [TextFrame](../../textframe/), elle modifie simplement son texte.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texte par défaut pour un nouveau [TextFrame](../../textframe/). |
## Remarques



Le code d'exemple suivant montre comment ajouter du texte filigrane dans PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 L'exemple suivant montre comment créer une zone de texte sur [Slide](../../slide/). 
```cpp
// Instancie la présentation
auto pres = System::MakeObject<Presentation>();

// Obtient la première diapositive de la présentation
auto slide = pres->get_Slides()->idx_get(0);
// Ajoute une AutoShape dont le type est Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Ajoute un TextFrame au rectangle
shape->AddTextFrame(u" ");
// Accède au TextFrame
auto txtFrame = shape->get_TextFrame();
// Crée l'objet Paragraph pour le TextFrame
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Crée un objet Portion pour le paragraphe
auto portion = para->get_Portions()->idx_get(0);
// Définit le texte
portion->set_Text(u"Aspose TextBox");
// Enregistre la présentation sur le disque
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 L'exemple suivant montre comment ajouter une colonne dans la zone de texte. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Obtient la première diapositive de la présentation
auto slide = presentation->get_Slides()->idx_get(0);
// Ajoute une AutoShape dont le type est Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Ajoute un TextFrame au rectangle
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Obtient le format de texte du TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Spécifie le nombre de colonnes dans le TextFrame
format->set_ColumnCount(3);
// Spécifie l'espacement entre les colonnes
format->set_ColumnSpacing(10);
// Enregistre la présentation
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../itextframe/)
* Classe [String](../../../system/string/)
* Classe [AutoShape](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)