---
title: get_HideInk()
second_title: Référence de l'API Aspose.Slides pour C++
description: Affiche ou masque les éléments Ink dans le document exporté.
type: docs
weight: 1
url: /fr/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() méthode


Affiche ou masque les éléments [Ink](../../../aspose.slides.ink/) dans le document exporté.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Remarques


La valeur par défaut est false. 

L'exemple suivant montre comment masquer les éléments [Ink](../../../aspose.slides.ink/) dans le document PDF exporté :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Voir aussi

* Classe [IInkOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)