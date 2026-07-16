---
title: get_CaptionTracks()
second_title: Aspose.Slides pour C++ Référence API
description: Obtient la collection de sous-titres fermés associés à la trame audio. Cette propriété est en lecture seule et renvoie une ICaptionsCollection contenant toutes les pistes de sous-titres.
type: docs
weight: 456
url: /fr/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() méthode

Obtient la collection de sous-titres fermés associés à la trame audio. Cette propriété est en lecture seule et renvoie un [ICaptionsCollection](../../icaptionscollection/) contenant toutes les pistes de sous-titres.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
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
        // Enregistrer les données binaires de la piste de sous-titres dans un fichier .vtt
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
* Classe [AudioFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)