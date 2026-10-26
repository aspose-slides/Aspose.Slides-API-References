---
title: set_SkipJavaScriptLinks()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie si les hyperliens avec des appels JavaScript doivent être ignorés lors de l'enregistrement de la présentation. Écrire bool. La valeur par défaut est false.
type: docs
weight: 118
url: /fr/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) méthode


Spécifie si les hyperliens avec des appels JavaScript doivent être ignorés lors de l'enregistrement de la présentation. Écrire **bool**. La valeur par défaut est **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Remarques


Lorsque cette propriété est définie sur **true**, les hyperliens avec des appels JavaScript seront ignorés lors de l'enregistrement.

Lorsque cette propriété est définie sur **false**, tous les hyperliens seront enregistrés.

Exemple:
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