---
title: SetColorMatrix()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 색상 보정 매트릭스를 설정합니다.
type: docs
weight: 183
url: /ko/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) 메서드

색상 보정 매트릭스를 설정합니다.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | 설정할 색상 보정 매트릭스 |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | 색상 보정 매트릭스에 의해 영향을 받는 이미지와 색상의 유형을 지정합니다 |
| type | [ColorAdjustType](../../coloradjusttype/) | 색상 보정 매트릭스를 설정할 객체 유형을 지정합니다 |

## 참고

* 열거형 [ColorMatrixFlag](../../colormatrixflag/)
* 열거형 [ColorAdjustType](../../coloradjusttype/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ColorMatrix](../../colormatrix/)
* 클래스 [ImageAttributes](../)
* 네임스페이스 [System::Drawing::Imaging](../../)
* 라이브러리 [Aspose.Slides](../../../)