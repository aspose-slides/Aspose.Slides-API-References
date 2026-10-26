---
title: get_SkipJavaScriptLinks()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation. Lire bool. La valeur par défaut est false.
type: docs
weight: 105
url: /fr/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() méthode


Spécifie s’il faut ignorer les hyperliens contenant des appels JavaScript lors de l’enregistrement de la présentation. Lire **bool**. La valeur par défaut est **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## Remarques


Lorsque cette propriété est définie sur **true**, les hyperliens contenant des appels JavaScript seront ignorés lors de l’enregistrement.

Lorsque cette propriété est définie sur **false**, tous les hyperliens seront enregistrés.

Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## Voir aussi

* Classe [SaveOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)