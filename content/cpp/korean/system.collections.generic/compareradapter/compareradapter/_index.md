---
title: ComparerAdapter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 사용 가능한 비교기가 없는 어댑터를 생성합니다.
type: docs
weight: 1
url: /ko/system.collections.generic/compareradapter/compareradapter/
---
## ComparerAdapter::ComparerAdapter() 생성자

사용 가능한 비교기가 없는 어댑터를 생성합니다.

```cpp
System::Collections::Generic::ComparerAdapter<T>::ComparerAdapter()
```

## ComparerAdapter::ComparerAdapter(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) 생성자

어댑터를 생성합니다.

```cpp
System::Collections::Generic::ComparerAdapter<T>::ComparerAdapter(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | 사용할 비교기 객체. |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IComparer](../../icomparer/)
* 구조체 [ComparerAdapter](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)