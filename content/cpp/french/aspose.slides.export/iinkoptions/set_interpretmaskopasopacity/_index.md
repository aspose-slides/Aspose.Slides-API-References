---
title: set_InterpretMaskOpAsOpacity()
second_title: Référence de l'API Aspose.Slides pour C++
description: Utilise l'opération ROP ou l'opacité pour le rendu du pinceau.
type: docs
weight: 40
url: /fr/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) méthode

Utilise l'opération ROP ou l'opacité pour le rendu du pinceau.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Remarques

La valeur par défaut est true. 

L'exemple suivant montre comment définir en utilisant ROP pour exporter les éléments [Ink](../../../aspose.slides.ink/) :

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Voir aussi

* Classe [IInkOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)