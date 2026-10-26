---
title: get_TrimFromStart()
second_title: Référence API Aspose.Slides pour C++
description: Début du rognage [ms]
type: docs
weight: 209
url: /fr/aspose.slides/videoframe/get_trimfromstart/
---
## VideoFrame::get_TrimFromStart() méthode


Début du rognage [ms]

```cpp
float Aspose::Slides::VideoFrame::get_TrimFromStart() override
```

## Remarques


Exemple: 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::ArrayPtr<uint8_t> content = System::IO::File::ReadAllBytes(u"video.mp4");
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(content);
System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 100.0f, 100.0f, video);

//définir le temps de début du rognage 1sec
videoFrame->set_TrimFromStart(1000.0f);

//définir le temps de fin du rognage 2sec
videoFrame->set_TrimFromEnd(2000.0f);
```

## Voir aussi

* Classe [VideoFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)