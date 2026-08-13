---
title: GroupEnumerable()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 1
url: /ko/system.collections.generic.details/groupenumerable/groupenumerable/
---
## GroupEnumerable::GroupEnumerable(SharedPtr\<IEnumerable\<Source\>\>, const Func\<Source, Key\>\&, const System::Func\<Source, Element\>\&) 생성자




```cpp
System::Collections::Generic::Details::GroupEnumerable<Source, Key, Element>::GroupEnumerable(SharedPtr<IEnumerable<Source>> sourceEnumerable, const Func<Source, Key> &keyPredicate, const System::Func<Source, Element> &elementSelector=System::Func<Source, Element>([](const Source &s) { return s;}))
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [Func](../../../system/func/)
* 클래스 [GroupEnumerable](../)
* 네임스페이스 [System::Collections::Generic::Details](../../)
* 라이브러리 [Aspose.Slides](../../../)