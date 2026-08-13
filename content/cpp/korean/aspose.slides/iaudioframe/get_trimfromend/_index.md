---
title: get_TrimFromEnd()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 재생 중 미디어 끝에서 제거될 시간 길이를 밀리초 단위로 지정합니다. 읽기 float.
type: docs
weight: 430
url: /ko/aspose.slides/iaudioframe/get_trimfromend/
---
## IAudioFrame::get_TrimFromEnd() 메서드


재생 중 미디어 끝에서 제거될 시간 길이를 밀리초 단위로 지정합니다. 읽기 **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromEnd()=0
```

## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 오디오 프레임 추가
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// 끝 트리밍 시간을 2초로 설정
audioFrame->set_TrimFromEnd(2000.0f);
```

## 참조

* 클래스 [IAudioFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)