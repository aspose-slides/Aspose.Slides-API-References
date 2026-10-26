---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 클릭할 때 매크로 하이퍼링크를 설정합니다.
type: docs
weight: 79
url: /ko/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) 메서드


클릭할 때 매크로 하이퍼링크를 설정합니다.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | 매크로의 이름 |

### 반환값

[Hyperlink](../../hyperlink/) 객체 [IHyperlink](../../ihyperlink/)
## 비고



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```




## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IHyperlink](../../ihyperlink/)
* 클래스 [String](../../../system/string/)
* 클래스 [IHyperlinkManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)