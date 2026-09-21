---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/loadoptions/delete_embedded_binary_objects/
weight: 70
---
## delete_embedded_binary_objects 속성
Aspose.Slides가 프레젠테이션을 로드하는 동안 모든 포함된 바이너리 개체를 삭제할지 여부를 결정합니다.
            
포함된 바이너리 개체의 유형:


* VBA Project [`IPresentation.vba_project`](/slides/python-net/ko/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/ko/aspose.slides/icontrol/active_x_control_binary)


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


### 참조
* 클래스 [`LoadOptions`](/slides/python-net/ko/aspose.slides/loadoptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)