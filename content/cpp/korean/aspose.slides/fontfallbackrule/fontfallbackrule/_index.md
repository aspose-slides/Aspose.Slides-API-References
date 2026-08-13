---
title: FontFallBackRule()
second_title: Aspose.Slides C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 66
url: /ko/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) 생성자


새 인스턴스를 생성합니다.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | **uint32_t** | 유니코드 범위의 시작 인덱스 |
| endIndex | **uint32_t** | 유니코드 범위의 끝 인덱스 |
| fontNames | [System::String](../../../system/string/) | FallBack을 위한 글꼴 이름 또는 여러 이름(쉼표로 구분) |
## 비고



```cpp
// FantFallBackRule의 새 인스턴스를 하나의 글꼴로 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// FantFallBackRule의 새 인스턴스를 여러 글꼴로 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) 생성자


새 인스턴스를 생성합니다.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | **uint32_t** | 유니코드 범위의 시작 인덱스 |
| endIndex | **uint32_t** | 유니코드 범위의 끝 인덱스 |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | FallBack을 위한 글꼴 이름 또는 여러 이름(쉼표로 구분) |
## 비고



```cpp
// 두 개의 글꼴로 FantFallBackRule의 새 인스턴스를 생성합니다
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// 여러 글꼴로 FantFallBackRule의 새 인스턴스를 생성합니다.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)