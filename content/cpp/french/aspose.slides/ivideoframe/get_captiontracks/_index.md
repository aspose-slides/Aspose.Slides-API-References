---
title: get_CaptionTracks()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère la collection des sous-titres fermés associés à la trame audio. Cette propriété est en lecture seule et renvoie une ICaptionsCollection contenant toutes les pistes de sous-titres.
type: docs
weight: 261
url: /fr/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() méthode


Récupère la collection des sous-titres fermés associés à la trame audio. Cette propriété est en lecture seule et renvoie un [ICaptionsCollection](../../icaptionscollection/) contenant toutes les pistes de sous-titres.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"video with captions.pptx");

for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    System::SharedPtr<IVideoFrame> videoFrame = System::AsCast<IVideoFrame>(shape);
    if (videoFrame != nullptr)
    {
        continue;
    }

    for (auto&& captionTrack : videoFrame->get_CaptionTracks())
    {
        // Extrait les données binaires des sous-titres et les enregistre dans le fichier
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptionsCollection](../../icaptionscollection/)
* Classe [IVideoFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)