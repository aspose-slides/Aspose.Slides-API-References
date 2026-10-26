---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 shape collection에 삽입합니다.
type: docs
weight: 235
url: /ko/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) method

새 외부 오디오 파일에 연결된 새로운 오디오 프레임을 생성하고 지정된 인덱스에 shape collection에 삽입합니다.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 오디오 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트)입니다. |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트)입니다. |
| width | **float** | 새 오디오 프레임의 너비(포인트)입니다. |
| height | **float** | 새 오디오 프레임의 높이(포인트)입니다. |
| fname | [System::String](../../../system/string/) | 연결할 외부 오디오 파일의 경로나 이름입니다. |

### 반환 값

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)