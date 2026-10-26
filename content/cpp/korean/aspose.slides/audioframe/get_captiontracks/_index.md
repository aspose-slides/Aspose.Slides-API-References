---
title: get_CaptionTracks()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 오디오 프레임에 연결된 닫힌 캡션 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 ICaptionsCollection을 반환합니다.
type: docs
weight: 456
url: /ko/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() 메서드


오디오 프레임에 연결된 닫힌 캡션 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [ICaptionsCollection](../../icaptionscollection/) 를 반환합니다.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## 비고


예:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // 캡션 트랙의 이진 데이터를 .vtt 파일로 저장
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ICaptionsCollection](../../icaptionscollection/)
* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)