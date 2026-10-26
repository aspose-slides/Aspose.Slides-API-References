---
title: get_TrimFromEnd()
second_title: Aspose.Slides C++용 API 참조
description: 재생 중 미디어 끝에서 제거되는 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기 float.
type: docs
weight: 430
url: /ko/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() 메서드

재생 중 미디어 끝에서 제거될 시간 지속 시간을 밀리초 단위로 지정합니다. 읽기 **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## 비고

예제:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 오디오 프레임 추가
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 끝 트리밍 시간을 2초로 설정
audioFrame->set_TrimFromEnd(2000.0f);
```

## 관련 항목

* 클래스 [AudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)