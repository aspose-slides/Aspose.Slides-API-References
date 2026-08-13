---
title: IndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 특정 수학 요소의 인덱스를 결정합니다.
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) 메서드


컬렉션에서 특정 수학 요소의 인덱스를 결정합니다.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 컬렉션에서 찾을 요소. |

### 반환 값

*item*이 컬렉션에 있으면 해당 인덱스를 반환하고, 없으면 -1을 반환합니다.
## 비고



예: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathElementCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)