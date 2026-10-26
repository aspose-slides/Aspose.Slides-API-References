---
title: get_Audios()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur lesbar IAudioCollection.
type: docs
weight: 222
url: /de/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() Methode

Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur lesbar [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Hinweise

Die folgenden Beispiele zeigen, wie ein Hyperlink zu einer Audiodatei hinzugefügt wird.
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioCollection](../../iaudiocollection/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)