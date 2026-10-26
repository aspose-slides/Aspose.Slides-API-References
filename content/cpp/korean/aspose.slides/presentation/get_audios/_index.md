---
title: get_Audios()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션에 포함된 모든 임베드된 오디오 파일의 컬렉션을 반환합니다. 읽기 전용 IAudioCollection.
type: docs
weight: 222
url: /ko/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() 메서드

프레젠테이션에 포함된 모든 임베드된 오디오 파일의 컬렉션을 반환합니다. 읽기 전용 [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## 비고

다음 예제는 오디오 파일에 하이퍼링크를 추가하는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudioCollection](../../iaudiocollection/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)