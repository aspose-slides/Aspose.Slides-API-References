---
title: CustomLineCap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 속성을 가진 사용자 정의 라인 캡을 나타내는 CustomLineCap 클래스의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) 생성자

지정된 속성을 가진 사용자 정의 라인 캡을 나타내는 [CustomLineCap](../) 클래스를 새 인스턴스로 생성합니다.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 사용자 정의 캡에 대한 채우기를 지정합니다 |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 사용자 정의 캡의 외곽선을 지정합니다 |
| baseCap | [LineCap](../../linecap/) | 사용자 정의 캡이 만들어지는 기본 라인 캡 |
| baseInset | **float** | 라인과 캡 사이의 거리를 지정합니다 |

## 관련 항목

* 열거형 [LineCap](../../linecap/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [GraphicsPath](../../graphicspath/)
* 클래스 [CustomLineCap](../)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* 라이브러리 [Aspose.Slides](../../../)