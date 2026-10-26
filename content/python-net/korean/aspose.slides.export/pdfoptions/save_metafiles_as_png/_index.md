---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png 속성
프레젠테이션에서 사용되는 모든 메타파일을 PNG 이미지로 변환하려면 true로 설정합니다.
            읽기/쓰기 **bool**.

### 비고

기본값은 **true** 입니다.
            Pdf 문서는 벡터 그래픽 및 래스터 이미지를 포함할 수 있습니다. 
            SaveMetafilesAsPng가 true로 설정되면 소스 Metafile 이미지가 Png 형식으로 변환되어 Pdf에 래스터 이미지로 저장됩니다. SaveMetafilesAsPng가 false로 설정되면 소스 Metafile이 Pdf 벡터 그래픽으로 변환됩니다. 각 접근 방식에는 장점과 단점이 있습니다. 예를 들어 Metafile이 PNG로 변환될 경우, 결과 문서 크기 조정 시 품질 손실이 발생할 수 있습니다. Metafile이 Pdf 벡터 그래픽으로 변환될 경우, Pdf 뷰어 도구에서 성능 문제가 발생할 수 있습니다.

### 정의:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### 참조
* 클래스 [`PdfOptions`](/slides/python-net/ko/aspose.slides.export/pdfoptions)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)