---
title: FromFile()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 파일에서 Image 객체를 생성합니다.
type: docs
weight: 352
url: /ko/system.drawing/image/fromfile/
---
## Image::FromFile(const String\&, bool) 메서드


지정된 파일에서 [Image](../) 객체를 생성합니다.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromFile(const String &filename, bool use_embedded_color_management=false)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 이미지 데이터를 포함하는 파일의 이름 |
| use_embedded_color_management | **bool** | 무시됨 |

### 반환 값

생성된 [Image](../) 객체에 대한 공유 포인터입니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Image](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)