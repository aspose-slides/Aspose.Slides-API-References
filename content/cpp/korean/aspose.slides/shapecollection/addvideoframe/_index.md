---
title: AddVideoFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 비디오 프레임을 생성하고 이를 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 209
url: /ko/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) 메서드

새 비디오 프레임을 생성하고 이를 도형 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 비디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 비디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 비디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 비디오 프레임의 높이(포인트 단위). |
| fname | [System::String](../../../system/string/) | 삽입할 비디오 파일의 경로 또는 이름. |

### 반환 값

새로 생성된 [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) 메서드

새 비디오 프레임을 생성하고 이를 도형 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 새 비디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 비디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 비디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 비디오 프레임의 높이(포인트 단위). |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | 비디오 프레임에 삽입할 [IVideo](../../ivideo/). |

### 반환 값

새로 생성된 [IVideoFrame](../../ivideoframe/).

## 또한 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IVideoFrame](../../ivideoframe/)
* 클래스 [String](../../../system/string/)
* 클래스 [ShapeCollection](../)
* 클래스 [IVideo](../../ivideo/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)