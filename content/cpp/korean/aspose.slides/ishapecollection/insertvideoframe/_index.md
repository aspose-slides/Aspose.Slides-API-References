---
title: InsertVideoFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 비디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.
type: docs
weight: 183
url: /ko/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) 메서드

새 비디오 프레임을 생성하고 지정된 인덱스에 shape 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 비디오 프레임을 삽입할 0 기반 인덱스. |
| x | **float** | 새 비디오 프레임의 x 좌표, 포인트 단위. |
| y | **float** | 새 비디오 프레임의 y 좌표, 포인트 단위. |
| width | **float** | 새 비디오 프레임의 너비, 포인트 단위. |
| height | **float** | 새 비디오 프레임의 높이, 포인트 단위. |
| fname | [System::String](../../../system/string/) | 삽입할 비디오 파일의 경로나 이름. |

### 반환값

새로 생성된 [IVideoFrame](../../ivideoframe/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IVideoFrame](../../ivideoframe/)
* 클래스 [String](../../../system/string/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)