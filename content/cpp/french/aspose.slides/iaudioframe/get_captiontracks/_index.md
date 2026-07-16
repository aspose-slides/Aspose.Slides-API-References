---
title: get_CaptionTracks()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la collection des légendes fermées associées à la trame audio. Cette propriété est en lecture seule et renvoie une ICaptionsCollection contenant toutes les pistes de légendes.
type: docs
weight: 456
url: /fr/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() méthode

Obtient la collection des légendes fermées associées à la trame audio. Cette propriété est en lecture seule et renvoie un [ICaptionsCollection](../../icaptionscollection/) contenant toutes les pistes de légendes.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
```

## Remarques


Exemple : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Enregistrer les données binaires de la piste de légende dans un fichier .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptionsCollection](../../icaptionscollection/)
* Classe [IAudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)