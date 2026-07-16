---
title: WriteAsEmf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Enregistre le contenu de la diapositive sous forme de fichier EMF.
type: docs
weight: 170
url: /fr/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) méthode


Enregistre le contenu de la diapositive sous forme de fichier EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux cible |
## Remarques



L'exemple de code suivant montre comment convertir la première diapositive d'une présentation PowerPoint en métafichier. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Enregistre la première diapositive sous forme de métafichier
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [Slide](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)