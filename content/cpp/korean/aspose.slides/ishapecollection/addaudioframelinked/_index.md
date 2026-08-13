---
title: AddAudioFrameLinked()
second_title: Aspose.Slides C++용 API 참조
description: 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 이를 모양 컬렉션의 끝에 추가합니다.
type: docs
weight: 222
url: /ko/aspose.slides/ishapecollection/addaudioframelinked/
---
## IShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) 메서드


새 오디오 프레임을 외부 오디오 파일에 연결하고, 이를 모양 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname)=0
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | **float** | 새 오디오 프레임의 x 좌표이며, 포인트 단위입니다. |
| y | **float** | 새 오디오 프레임의 y 좌표이며, 포인트 단위입니다. |
| width | **float** | 새 오디오 프레임의 너비이며, 포인트 단위입니다. |
| height | **float** | 새 오디오 프레임의 높이이며, 포인트 단위입니다. |
| fname | [System::String](../../../system/string/) | 연결할 외부 오디오 파일의 경로나 이름입니다. |

### 반환값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudioFrame](../../iaudioframe/)
* 클래스 [String](../../../system/string/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)