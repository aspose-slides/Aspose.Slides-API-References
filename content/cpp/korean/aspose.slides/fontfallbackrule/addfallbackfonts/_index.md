---
title: AddFallBackFonts()
second_title: Aspose.Slides C++ API 참조
description: 새 폰트(들)를 FallBack 폰트 목록에 추가합니다.
type: docs
weight: 79
url: /ko/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) 메서드


새 폰트(들)를 FallBack 폰트 목록에 추가합니다.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | FallBack용 쉼표로 구분된 폰트의 이름 또는 이름들 |
## 비고



```cpp
// FontFallBackRule의 새 인스턴스를 생성합니다
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// 규칙에 두 번째 폰트를 추가합니다
newRule->AddFallBackFonts(u"MS Gothic");
// 규칙에 세 번째와 네 번째 폰트를 추가합니다
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) 메서드


새 폰트를 FallBack 폰트 목록에 추가합니다.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | FallBack용 쉼표로 구분된 폰트의 이름 또는 이름들 |
## 비고



```cpp
//FontFallBackRule의 새 인스턴스를 생성합니다
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//규칙에 또 다른 세 개의 폰트를 추가합니다
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [FontFallBackRule](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)