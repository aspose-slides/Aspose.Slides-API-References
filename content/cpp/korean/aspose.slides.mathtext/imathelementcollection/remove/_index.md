---
title: Remove()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) 메서드

컬렉션에서 특정 객체의 첫 번째 발생을 제거합니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 컬렉션에서 제거할 객체. |

### 반환값

컬렉션에서 *item*이(가) 성공적으로 제거되면 true, 그렇지 않으면 false. 이 메서드는 원본 컬렉션에 *item*이(가) 없을 경우에도 false를 반환합니다.

## 비고



예제: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathElementCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)