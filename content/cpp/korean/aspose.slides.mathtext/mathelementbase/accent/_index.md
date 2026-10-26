---
title: Accent()
second_title: Aspose.Slides for C++ API 참조
description: 이 요소의 위에 악센트 표시(문자)를 설정합니다
type: docs
weight: 196
url: /ko/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) 메서드


이 요소 위에 악센트 표시(문자)를 설정합니다

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| accentCharacter | char16_t | 악센트 문자. 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다 |

### 반환값

새 인스턴스 유형 [IMathAccent](../../imathaccent/)
## 비고



예: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathAccent](../../imathaccent/)
* 클래스 [MathElementBase](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)