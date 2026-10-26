---
title: InsertVideoFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 비디오 프레임을 생성하고 지정된 인덱스에 쉐이프 컬렉션에 삽입합니다.
type: docs
weight: 222
url: /ko/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) 메서드

새 비디오 프레임을 생성하고 지정된 인덱스에 쉐이프 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 비디오 프레임을 삽입할 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 비디오 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 비디오 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 비디오 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 비디오 프레임의 높이(포인트 단위)입니다. |
| fname | [System::String](../../../system/string/) | 삽입할 비디오 파일의 경로나 이름입니다. |

### 반환 값

새로 생성된 [IVideoFrame](../../ivideoframe/).

## 관련 정보

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IVideoFrame](../../ivideoframe/)
* 클래스 [String](../../../system/string/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)