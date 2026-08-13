---
title: AddControl()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에 새 컨트롤을 생성하고 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides/icontrolcollection/addcontrol/
---
## IControlCollection::AddControl(ControlType, float, float, float, float) 메서드

새 컨트롤을 생성하고 컬렉션에 추가합니다.

```cpp
virtual System::SharedPtr<IControl> Aspose::Slides::IControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | 추가할 컨트롤의 유형. |
| x | **float** | 도형 프레임 왼쪽 측면의 X 좌표. |
| y | **float** | 도형 프레임 상단 측면의 Y 좌표. |
| width | **float** | 도형 프레임의 너비. |
| height | **float** | 도형 프레임의 높이. |

### 반환값

생성된 컨트롤 [IControl](../../icontrol/).

## 참조

* Enum [ControlType](../../controltype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IControl](../../icontrol/)
* 클래스 [IControlCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)