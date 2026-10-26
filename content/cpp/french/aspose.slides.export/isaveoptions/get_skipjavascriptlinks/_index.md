---
title: get_SkipJavaScriptLinks()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation. Lecture bool. La valeur par défaut est false.
type: docs
weight: 105
url: /fr/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() méthode

Spécifie s’il faut ignorer les hyperliens contenant des appels JavaScript lors de l’enregistrement de la présentation. Lecture **bool**. La valeur par défaut est **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## Remarques

Lorsque cette propriété est définie sur **true**, les hyperliens contenant des appels JavaScript seront ignorés lors de l’enregistrement.

Lorsque cette propriété est définie sur **false**, tous les hyperliens seront enregistrés.

Exemple:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Voir aussi

* Classe [ISaveOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)