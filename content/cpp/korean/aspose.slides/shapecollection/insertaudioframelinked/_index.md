---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 해당 프레임을 Shape 컬렉션에 삽입합니다.
type: docs
weight: 274
url: /ko/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) 메서드

외부 오디오 파일에 연결된 새로운 오디오 프레임을 생성하고 지정된 인덱스에 해당 프레임을 Shape 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 오디오 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 오디오 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 오디오 프레임의 높이(포인트 단위)입니다. |
| fname | [System::String](../../../system/string/) | 연결할 외부 오디오 파일의 경로나 이름입니다. |

### 반환 값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudioFrame](../../iaudioframe/)
* 클래스 [String](../../../system/string/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)