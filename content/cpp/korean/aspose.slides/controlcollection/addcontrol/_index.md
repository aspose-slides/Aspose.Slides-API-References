---
title: AddControl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 컨트롤을 생성하고 컬렉션에 추가합니다.
type: docs
weight: 40
url: /ko/aspose.slides/controlcollection/addcontrol/
---
## ControlCollection::AddControl(ControlType, float, float, float, float) 메서드

새 컨트롤을 생성하고 컬렉션에 추가합니다.

```cpp
System::SharedPtr<IControl> Aspose::Slides::ControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | 추가할 컨트롤의 유형. |
| x | **float** | 모양 프레임의 왼쪽 면에 대한 X 좌표. |
| y | **float** | 모양 프레임의 상단 면에 대한 Y 좌표. |
| width | **float** | 모양 프레임의 너비. |
| height | **float** | 모양 프레임의 높이. |

### 반환값

생성된 컨트롤.

## 기타 참조

* 열거형 [ControlType](../../controltype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IControl](../../icontrol/)
* 클래스 [ControlCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)