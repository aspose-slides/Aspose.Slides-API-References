---
title: FromStream()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 스트림에서 Image 객체를 생성합니다.
type: docs
weight: 339
url: /ko/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) 메서드


Creates an [Image](../) object from the specified stream.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 이미지 데이터를 포함하는 스트림 |
| use_embedded_color_management | **bool** | 무시됨 |
| validate_image_data | **bool** | 무시됨 |

### Return Value

생성된 [Image](../) 객체에 대한 공유 포인터.

## See Also

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Image](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)