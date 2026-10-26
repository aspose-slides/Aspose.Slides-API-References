---
title: register_ink_effect_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
잉크 브러시의 시각 효과를 시뮬레이션하기 위해 사용되는 사용자 정의 이미지 모음에 이미지를 등록합니다.
            이러한 이미지는 Galaxy, Rainbow 등과 같은 특정 [`InkEffectType`](/slides/python-net/ko/aspose.slides.ink/inkeffecttype) 값을 사용하여 잉크를 렌더링할 때 사용됩니다. 자체 이미지를 제공함으로써 각 잉크 효과가 나타나는 방식을 제어할 수 있습니다.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/ko/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/ko/aspose.slides/iimage) |  |

### 비고

이 메서드는 기본 잉크 효과 텍스처를 사용자 정의 텍스처로 교체할 수 있게 하며, 기본 자산이 라이선스로 제한되거나 런타임에 사용할 수 없을 때 특히 유용합니다. 각 등록된 값 쌍은 [`InkEffectType`](/slides/python-net/ko/aspose.slides.ink/inkeffecttype) 값을 해당 [`IImage`](/slides/python-net/ko/aspose.slides/iimage) 객체(예: Bitmap 또는 Aspose 이미지 인터페이스)와 연결해야 합니다.



### 참고
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 클래스 [`Ink`](/slides/python-net/ko/aspose.slides.ink/ink)
* 열거형 [`InkEffectType`](/slides/python-net/ko/aspose.slides.ink/inkeffecttype)
* 모듈 [`aspose.slides.ink`](/slides/python-net/ko/aspose.slides.ink)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)