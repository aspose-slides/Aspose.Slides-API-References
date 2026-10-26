---
title: Control class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/control/
---
## Control 클래스

ActiveX 컨트롤을 나타냅니다.

Control 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`persistence`](/slides/python-net/ko/aspose.slides/control/persistence/) | Gets the method used to store properties of the ActiveX control.<br/>            읽기 전용 [`PersistenceType`](/slides/python-net/ko/aspose.slides/persistencetype). |
| [`name`](/slides/python-net/ko/aspose.slides/control/name/) | Gets or sets the name of this control.<br/>            읽기/쓰기 **str**. |
| [`class_id`](/slides/python-net/ko/aspose.slides/control/class_id/) | Gets class id of this control.<br/>            읽기 전용 **System.Guid**. |
| [`substitute_picture_format`](/slides/python-net/ko/aspose.slides/control/substitute_picture_format/) | Returns Control image fill properties object.<br/>            읽기 전용 [`IPictureFillFormat`](/slides/python-net/ko/aspose.slides/ipicturefillformat). |
| [`frame`](/slides/python-net/ko/aspose.slides/control/frame/) | Returns or sets control's frame.<br/>            읽기/쓰기 [`IShapeFrame`](/slides/python-net/ko/aspose.slides/ishapeframe). |
| [`properties`](/slides/python-net/ko/aspose.slides/control/properties/) | Returns a collection of ActiveX properties.<br/>            참고: Aspose.Slides supports only XML based ActiveX properties. If properties stored in binary format, this property will return None.<br/>            읽기 전용 [`IControlPropertiesCollection`](/slides/python-net/ko/aspose.slides/icontrolpropertiescollection). |
| [`active_x_control_binary`](/slides/python-net/ko/aspose.slides/control/active_x_control_binary/) | Specifies the persistence of an ActiveX control when the method used to persist is either PersistStream, PersistStreamInit or PersistStorage. |
| [`slide`](/slides/python-net/ko/aspose.slides/control/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/control/presentation/) |  |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)