---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 클릭 시 외부 하이퍼링크를 설정합니다.
type: docs
weight: 1
url: /ko/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) 메서드

클릭 시 외부 하이퍼링크를 설정합니다.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## 비고

다음 샘플 코드는 [Hyperlink](../../hyperlink/)를 사용하여 텍스트 상자를 추가하는 방법을 보여줍니다.
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// 프레젠테이션에서 첫 번째 슬라이드를 가져옵니다
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// 유형을 Rectangle로 설정한 AutoShape 객체를 추가합니다
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// AutoShape와 연결된 ITextFrame 속성에 접근합니다
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// 프레임에 일부 텍스트를 추가합니다
portion->set_Text(u"Aspose.Slides");

// 해당 부분 텍스트에 대한 하이퍼링크를 설정합니다
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// PPTX 프레젠테이션을 저장합니다
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IHyperlink](../../ihyperlink/)
* 클래스 [String](../../../system/string/)
* 클래스 [HyperlinkManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)