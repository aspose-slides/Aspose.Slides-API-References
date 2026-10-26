---
title: get_InterpretMaskOpAsOpacity()
second_title: Référence de l'API Aspose.Slides pour C++
description: Utilise l'opération ROP ou l'opacité pour le rendu du pinceau.
type: docs
weight: 27
url: /fr/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() méthode

Utilise l'opération ROP ou l'opacité pour rendre le pinceau.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Remarques

La valeur par défaut est true. 

L'exemple suivant montre comment configurer en utilisant ROP pour exporter des éléments [Ink](../../../aspose.slides.ink/) : 
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