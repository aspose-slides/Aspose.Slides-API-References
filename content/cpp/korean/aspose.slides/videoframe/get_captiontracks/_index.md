---
title: get_CaptionTracks()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 비디오 프레임과 연결된 폐쇄 자막 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 ICaptionsCollection을 반환합니다.
type: docs
weight: 261
url: /ko/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() 메서드


비디오 프레임과 연결된 폐쇄 캡션 컬렉션을 가져옵니다. 이 속성은 읽기 전용이며 모든 캡션 트랙을 포함하는 [ICaptionsCollection](../../icaptionscollection/)를 반환합니다.
```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
```

## 비고
예시: 
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
        // 캡션 바이너리 데이터를 추출하여 파일에 저장합니다.
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ICaptionsCollection](../../icaptionscollection/)
* 클래스 [VideoFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)