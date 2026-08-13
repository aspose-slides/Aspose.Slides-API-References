---
title: AddPath()
second_title: Aspose.Slides C++ API 참조
description: 지정된 경로를 현재 객체가 나타내는 경로에 추가합니다.
type: docs
weight: 222
url: /ko/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) 메서드

지정된 경로를 현재 객체가 나타내는 경로에 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | 추가할 경로 |
| connect | **bool** | True는 **path**의 마지막 첫 번째 도형이 현재 객체가 나타내는 경로의 마지막 도형의 일부임을 지정하고; false는 **path**의 첫 번째 도형과 현재 객체가 나타내는 경로의 마지막 도형이 별개의 도형임을 지정합니다. |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [GraphicsPath](../)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* 라이브러리 [Aspose.Slides](../../../)