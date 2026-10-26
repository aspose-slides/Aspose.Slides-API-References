---
title: AddFallBackFonts()
second_title: Aspose.Slides for C++ API 참조
description: 새 글꼴(들)을 FallBack 글꼴 목록에 추가합니다.
type: docs
weight: 40
url: /ko/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) 메서드

새 글꼴(들)을 FallBack 글꼴 목록에 추가합니다.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | FallBack용 글꼴 이름 또는 이름들(쉼표로 구분) |
## 비고



```cpp
//새로운 FantFallBackRule 인스턴스 생성
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//규칙에 두 번째 글꼴 추가
newRule->AddFallBackFonts(u"MS Gothic");
//규칙에 세 번째와 네 번째 글꼴 추가
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) 메서드

새 글꼴들을 FallBack 글꼴 목록에 추가합니다.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | FallBack용 글꼴 이름 또는 이름들(쉼표로 구분) |
## 비고



```cpp
//새로운 FontFallBackRule 인스턴스 생성
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//규칙에 또 다른 세 글꼴 추가
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## 관련 항목

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IFontFallBackRule](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)