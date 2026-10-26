---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects 속성
프리젠테이션 로드 중에 Aspose.Slides가 모든 임베디드 바이너리 객체를 삭제할지 여부를 결정합니다.
            
임베디드 바이너리 객체 유형:

* VBA 프로젝트 [`IPresentation.vba_project`](/slides/python-net/ko/aspose.slides/ipresentation/vba_project)
* OLE 객체 임베디드 데이터 [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX 컨트롤 바이너리 데이터 [`IControl.active_x_control_binary`](/slides/python-net/ko/aspose.slides/icontrol/active_x_control_binary)

읽기/쓰기 **bool**.

### 비고

기본값은 **false** 입니다.

### 정의:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### 참고
* 클래스 [`ILoadOptions`](/slides/python-net/ko/aspose.slides/iloadoptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)