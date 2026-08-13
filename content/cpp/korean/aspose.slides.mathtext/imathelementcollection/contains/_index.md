---
title: Contains()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에 특정 값이 포함되어 있는지 확인합니다.
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection::Contains(System::SharedPtr\<IMathElement\>) method


컬렉션에 특정 값이 포함되어 있는지 확인합니다.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Contains(System::SharedPtr<IMathElement> item)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 컬렉션에서 찾을 객체입니다. |

### 반환 값

*item*이 컬렉션에 있으면 true, 그렇지 않으면 false.

## 비고



예시: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = collection->Contains(plusElement);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathElementCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)