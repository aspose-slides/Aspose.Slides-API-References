---
title: AddAudioFrameLinked()
second_title: Aspose.Slides for C++ API 참조
description: 새로운 오디오 프레임을 생성하여 외부 오디오 파일에 연결하고 이를 Shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 261
url: /ko/aspose.slides/shapecollection/addaudioframelinked/
---
## ShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) 메서드

외부 오디오 파일에 연결된 새로운 오디오 프레임을 생성하고 이를 Shape 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 오디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 오디오 프레임의 높이(포인트 단위). |
| fname | [System::String](../../../system/string/) | 연결할 외부 오디오 파일의 경로나 이름. |

### 반환 값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudioFrame](../../iaudioframe/)
* 클래스 [String](../../../system/string/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)