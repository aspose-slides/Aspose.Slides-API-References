---
title: get_Count()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에 실제로 포함된 요소의 수를 가져옵니다. 읽기 전용 int32_t.
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() 메서드


컬렉션에 실제로 포함된 요소의 수를 가져옵니다. 읽기 전용 **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## 비고


예:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## 참조

* 클래스 [IMathElementCollection](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)