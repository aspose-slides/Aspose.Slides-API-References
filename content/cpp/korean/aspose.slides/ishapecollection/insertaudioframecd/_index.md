---
title: InsertAudioFrameCD()
second_title: Aspose.Slides for C++ API 참조
description: CD 트랙에 연결된 새로운 오디오 프레임을 생성하고 지정된 인덱스에 shape collection에 삽입합니다.
type: docs
weight: 209
url: /ko/aspose.slides/ishapecollection/insertaudioframecd/
---
## IShapeCollection::InsertAudioFrameCD(int32_t, float, float, float, float) 메서드


Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameCD(int32_t index, float x, float y, float width, float height)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 오디오 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 오디오 프레임의 x 좌표이며, 포인트 단위입니다. |
| y | **float** | 새 오디오 프레임의 y 좌표이며, 포인트 단위입니다. |
| width | **float** | 새 오디오 프레임의 너비이며, 포인트 단위입니다. |
| height | **float** | 새 오디오 프레임의 높이이며, 포인트 단위입니다. |

### Return Value

새로 생성된 [IAudioFrame](../../iaudioframe/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)