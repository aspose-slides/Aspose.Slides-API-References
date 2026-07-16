---
title: set_DisableFontLigatures()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur true, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur false.
type: docs
weight: 339
url: /fr/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISVGOptions::set_DisableFontLigatures(bool) méthode


Définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsqu'elle est définie sur **true**, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur **false**.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## Remarques



Exemple : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Désactiver les ligatures dans le rendu du texte

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Voir aussi

* Classe [ISVGOptions](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)