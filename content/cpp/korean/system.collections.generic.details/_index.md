---
title: "System::Collections::Generic::Details"
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 352
url: /ko/system.collections.generic.details/
---
## 클래스

| 클래스 | 설명 |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | IEnumerable.Cast() 및 IEnumerable.OfType() 확장 메서드에서 사용되는 열거형. |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | IEnumerable.Select() 확장 메서드에서 사용되는 열거형. |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | IEnumerable.Cast() 확장 메서드에서 사용되는 열거자. |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | IEnumerable.OfType() 확장 메서드에서 사용되는 열거자. |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | IEnumerable.Select() 확장 메서드에서 사용되는 열거자. |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## 구조체

| 구조체 | 설명 |
| --- | --- |
| [ComparerType](./comparertype/) | 'less' 의미를 사용하여 요소를 비교합니다. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | 'less' 의미를 사용하여 요소를 비교합니다. |
| [has_method_compareto](./has_method_compareto/) | 지정된 타입에 CompareTo 메서드가 존재하는지 확인합니다. 존재하면 std::true_type을 상속하고, 그렇지 않으면 std::false_type을 상속합니다. std::enable_if에서 사용할 수 있습니다. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | 지정된 타입에 CompareTo(SharedPtr<T>) 메서드가 존재하는지 확인합니다. 존재하면 std::true_type을 상속하고, 그렇지 않으면 std::false_type을 상속합니다. std::enable_if에서 사용할 수 있습니다. |
| [IsEqualExist](./isequalexist/) | 타입이 operator == 를 제공하는지 확인합니다. |
## 함수

| 함수 | 설명 |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | 인덱스가 컨테이너 크기를 제외한 범위를 벗어났는지 확인합니다. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | 인덱스가 컨테이너 크기를 제외한 범위를 벗어났는지 확인합니다. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | 인덱스가 컨테이너 크기를 포함한 범위를 벗어났는지 확인합니다. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | 인덱스가 컨테이너 크기를 포함한 범위를 벗어났는지 확인합니다. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | 특정 클래스에 operator == 가 있는지 판단하는 도우미 함수입니다. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | 특정 클래스에 operator == 가 있는지 판단하는 도우미 함수입니다. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | 컬렉션의 첫 번째 요소를 가져오려고 시도합니다. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | 조건 함수(predicate)에 만족하는 컬렉션의 첫 번째 요소를 가져오려고 시도합니다. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | 컬렉션의 마지막 요소를 가져오려고 시도합니다. |
## 타입별칭

| 타입별칭 | 설명 |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | operator == 존재 여부를 확인하기 위한 더미 타입 정의. |