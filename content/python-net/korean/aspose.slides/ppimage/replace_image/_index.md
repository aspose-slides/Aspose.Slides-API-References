---
title: replace_image method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ppimage/replace_image/
weight: 10
---
## replace_image(self, new_image_data) {#bytes}
이미지 데이터를 교체합니다.
새 이미지의 데이터입니다. newImageData 매개변수가 None인 경우.

```python
def replace_image(self, new_image_data):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_image_data | **bytes** |  |

## replace_image(self, new_image) {#iimage}
이미지 데이터를 교체합니다. 주의: Image가 메타파일인 경우 래스터화됩니다. 대신 ReplaceImage(byte[])를 사용하십시오.
새 이미지입니다. newImage 매개변수가 None인 경우.

```python
def replace_image(self, new_image):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_image | [`IImage`](/slides/python-net/ko/aspose.slides/iimage) |  |

## replace_image(self, new_image) {#ippimage}
이미지 데이터를 교체합니다.
새 IPPImage입니다. newImage 매개변수가 None인 경우.

```python
def replace_image(self, new_image):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_image | [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage) |  |

### 참고
* 클래스 [`IImage`](/slides/python-net/ko/aspose.slides/iimage)
* 클래스 [`IPPImage`](/slides/python-net/ko/aspose.slides/ippimage)
* 클래스 [`PPImage`](/slides/python-net/ko/aspose.slides/ppimage)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)