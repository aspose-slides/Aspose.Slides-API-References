---
title: set_InterpretMaskOpAsOpacity()
second_title: Référence de l'API Aspose.Slides pour C++
description: Utilise l'opération ROP ou l'opacité pour le rendu du pinceau.
type: docs
weight: 40
url: /fr/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) méthode


Utilise l'opération ROP ou l'opacité pour le rendu du pinceau.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
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

* Classe [InkOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)