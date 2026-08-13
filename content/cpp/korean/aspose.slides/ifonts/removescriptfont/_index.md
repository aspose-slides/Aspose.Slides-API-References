---
title: RemoveScriptFont()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 스크립트 태그와 연결된 글꼴 설정을 테마의 글꼴 컬렉션에서 제거합니다.
type: docs
weight: 118
url: /ko/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) 메서드


특정 스크립트 태그와 연결된 글꼴 설정을 테마의 글꼴 컬렉션에서 제거합니다.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 제거해야 하는 글꼴 설정과 관련된 BCP-47 스크립트 코드를 나타냅니다. |
## 비고



이 예제는 히브리어 스크립트에 대한 글꼴 매핑을 제거하는 방법을 보여줍니다: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [IFonts](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)