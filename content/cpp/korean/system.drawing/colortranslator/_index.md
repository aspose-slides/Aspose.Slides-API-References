---
title: ColorTranslator
second_title: Aspose.Slides for C++ API 레퍼런스
description: "색상 변환을 수행합니다. 이 클래스의 객체는 System::MakeObject() 함수만 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 이 포인터를 함수 인자로 전달하여 사용하십시오."
type: docs
weight: 66
url: /ko/system.drawing/colortranslator/
---
## ColorTranslator 클래스

색상 변환을 수행합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수만 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 이 포인터를 함수 인자로 전달하여 사용하십시오.

```cpp
class ColorTranslator
```

## Methods

| 메서드 | 설명 |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | 지정된 HTML 색상 표현을 동등한 [Color](../color/) 객체로 변환합니다. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | 지정된 [Windows](../../system.windows/) 색상을 동등한 [Color](../color/) 객체로 변환합니다. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | 지정된 [Color](../color/) 객체를 동등한 HTML 색상의 문자열 표현으로 변환합니다. |

## 참조

* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)