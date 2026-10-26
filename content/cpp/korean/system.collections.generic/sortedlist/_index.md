---
title: SortedList
second_title: Aspose.Slides for C++ API 참조
description: "FlatMap 구조를 래핑하는 정렬된 리스트입니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 생성하거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달하십시오."
type: docs
weight: 547
url: /ko/system.collections.generic/sortedlist/
---
## SortedList 클래스

FlatMap 구조를 래핑하는 정렬된 리스트입니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 생성하거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 래핑하고, 해당 포인터를 함수 인자로 전달하십시오.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | 키-값 쌍을 컨테이너에 추가합니다. |
| virtual void [Add](../icollection/add/)(const T&) | 요소를 컬렉션에 추가합니다. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | 컬렉션의 첫 번째 요소(있는 경우)를 가리키는 이터레이터를 반환합니다. 이 이터레이터는 [GetEnumerator()](../ienumerable/getenumerator/)가 T의 복사 객체를 반환하기 때문에 참조된 객체를 변경하는 데 사용할 수 없습니다. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | 컬렉션의 const 한정 인스턴스에서 첫 번째 요소(있는 경우)를 가리키는 이터레이터를 반환합니다. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | 컬렉션에서 첫 번째 const 한정 요소(있는 경우)를 가리키는 이터레이터를 반환합니다. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | 컬렉션의 마지막 const 한정 요소(있는 경우) 바로 뒤를 가리키는 이터레이터를 반환합니다. |
| virtual void [Clear](../icollection/clear/)() | 컬렉션의 모든 요소를 삭제합니다. |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | 요소가 컬렉션에 존재하는지 확인합니다. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | 컨테이너에 해당 키가 포함되어 있는지 확인합니다. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | 사전 내용을 기존 배열 요소에 복사합니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 컬렉션의 마지막 const 한정 요소(역순에서 첫 번째)로 가는 역방향 이터레이터를 반환합니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 컬렉션 시작 전의 존재하지 않는 const 한정 요소에 대한 역방향 이터레이터를 반환합니다. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | 컬렉션의 마지막 요소(있는 경우) 바로 뒤를 가리키는 이터레이터를 반환합니다. [GetEnumerator()](../ienumerable/getenumerator/)가 T의 복사 객체를 반환하기 때문에 이 이터레이터는 참조된 객체를 변경할 수 없습니다. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | 컬렉션의 const 한정 인스턴스에서 마지막 요소(있는 경우) 바로 뒤를 가리키는 이터레이터를 반환합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T1>::value&&\![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | 내부 용도 전용입니다. |
| int [get_Capacity](./get_capacity/)() const | 현재 리스트 용량을 반환합니다. |
| virtual int [get_Count](../icollection/get_count/)() const | 컬렉션의 요소 개수를 반환합니다. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | 컬렉션 크기가 고정되어 있는지 확인합니다. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 컬렉션이 읽기 전용인지 확인합니다. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | 컨테이너가 스레드 안전한지 확인합니다. |
| virtual [SharedPtr](../../system/sharedptr/)<[IList](../ilist/)<TKey>> [get_Keys](./get_keys/)() const | 키 컬렉션에 접근합니다. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | 컬렉션이 동기화되는 객체를 반환합니다. |
| virtual [SharedPtr](../../system/sharedptr/)<[IList](../ilist/)<TValue>> [get_Values](./get_values/)() const | 값 컬렉션에 접근합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 반환합니다. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | 현재 리스트를 반복하는 열거자를 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 반환합니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | 값을 찾으면 반환하고, 그렇지 않으면 **Value()**를 반환합니다. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | 값을 찾으면 반환하고, 그렇지 않으면 **defaultValue**를 반환합니다. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | 값을 찾으면 반환하고, 그렇지 않으면 **null**을 반환합니다. 이는 참조 타입에만 의미가 있습니다. |
| [ICollection](../icollection/icollection/)() | 기본 생성자입니다. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | 복사 생성자입니다. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | 이동 생성자입니다. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | Getter 함수입니다. |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | Setter 함수입니다. |
| int [IndexOfKey](./indexofkey/)(TKey) const | 특정 키를 찾습니다. |
| int [IndexOfValue](./indexofvalue/)(TValue) const | 특정 값을 찾습니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | 객체가 targetType이 설명하는 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | 시퀀스에 누산 함수 적용합니다. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | 시퀀스의 모든 요소가 조건을 만족하는지 판단합니다. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 시퀀스에 요소가 하나라도 있는지 판단합니다. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | 시퀀스에 요소가 존재하거나 조건을 만족하는지 판단합니다. |
| T [LINQ_Average](../ienumerable/linq_average/)() | 숫자값 시퀀스의 평균을 계산합니다. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | 입력 시퀀스 각 요소에 변환 함수를 적용하여 얻은 값들의 평균을 계산합니다. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | 요소들을 지정된 타입으로 캐스팅합니다. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | 두 시퀀스를 연결합니다. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 시퀀스에 지정된 값이 포함되어 있는지 판단합니다. |
| int [LINQ_Count](../ienumerable/linq_count/)() | 시퀀스의 요소 개수를 반환합니다 (직접 카운팅). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | 지정된 조건을 만족하는 시퀀스 요소 개수를 반환합니다. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 시퀀스에서 지정된 인덱스의 요소를 반환합니다. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 시퀀스에서 지정된 인덱스의 요소를 반환합니다. |
| T [LINQ_First](../ienumerable/linq_first/)() | 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | 지정된 조건을 만족하는 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 시퀀스의 첫 번째 요소를 반환하며, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | 조건을 만족하는 시퀀스의 첫 번째 요소를 반환하고, 없을 경우 기본값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | 시퀀스의 요소들을 그룹화합니다. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | 시퀀스의 요소들을 그룹화합니다. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 시퀀스의 마지막 요소를 반환합니다. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 시퀀스의 마지막 요소를 반환하며, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | 일반 시퀀스 각 요소에 변환 함수를 적용하고 최대 결과값을 반환합니다. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | 일반 시퀀스 각 요소에 변환 함수를 적용하고 최소 결과값을 반환합니다. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | 지정된 타입에 따라 시퀀스 요소를 필터링합니다. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | keySelector가 선택한 키 값을 기준으로 시퀀스 요소를 오름차순 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | keySelector가 선택한 키 값을 기준으로 시퀀스 요소를 내림차순 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 시퀀스 요소의 순서를 반전시킵니다. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | 시퀀스 요소를 변환합니다. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | 각 요소의 인덱스를 포함시켜 시퀀스 요소를 새로운 형태로 변환합니다. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | 시퀀스 각 요소를 투영하고 결과 시퀀스를 하나로 결합합니다. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | 시퀀스 시작부터 지정된 개수만큼 연속 요소를 건너뛰고 나머지를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 시퀀스 시작부터 지정된 개수의 연속 요소를 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 시퀀스에서 배열을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | 시퀀스에서 List<T>를 생성합니다. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | 지정된 프레디케이트에 따라 시퀀스를 필터링합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성하고 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | 복사 생성자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사를 가능하게 합니다. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | 이동 대입 연산자. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | 이동 대입 연산자. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | 대입 연산자. 실제로 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사를 가능하게 합니다. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 컬렉션의 마지막 요소(역순에서 첫 번째)로 가는 역방향 이터레이터를 반환합니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | const 한정 컬렉션의 마지막 요소(역순에서 첫 번째)로 가는 역방향 이터레이터를 반환합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | 키를 컨테이너에서 제거합니다. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | 요소를 컬렉션에서 삭제합니다. |
| void [RemoveAt](./removeat/)(int) | 지정된 위치의 항목을 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 공유 레퍼런스 카운트를 지정된 값만큼 감소시킵니다. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 컬렉션 시작 전의 존재하지 않는 요소에 대한 역방향 이터레이터를 반환합니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | const 한정 컬렉션 시작 전의 존재하지 않는 요소에 대한 역방향 이터레이터를 반환합니다. |
| void [set_Capacity](./set_capacity/)(int) | 현재 리스트 용량을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 강한 포인터 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 반환합니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하면 안 되며 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| [SortedList](./sortedlist/)() | 빈 리스트를 생성합니다. |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<TKey>>) | 빈 리스트를 생성합니다. |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>) | 복사 생성자입니다. |
| [SortedList](./sortedlist/)(const [map_t](./map_t/)&) | 복사 생성자입니다. |
| [SortedList](./sortedlist/)(int) | 빈 리스트를 생성합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 객체를 문자열로 변환합니다. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | 값을 찾아서 있으면 반환합니다. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | 현재 컨테이너의 begin const 이터레이터 구현을 반환합니다. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | 현재 컨테이너의 begin 이터레이터 구현을 반환합니다. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | 현재 컨테이너의 end const 이터레이터 구현을 반환합니다. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | 현재 컨테이너의 end 이터레이터 구현을 반환합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하면 안 되며 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하면 안 되며 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~ICollection](../icollection/~icollection/)() | 소멸자입니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴하고 모든 내부 데이터 구조를 해제합니다. |

## 타입정의

| 타입정의 | 설명 |
| --- | --- |
| [KeyCollection](./keycollection/) | 키 컬렉션 타입. |
| [ValueCollection](./valuecollection/) | 값 컬렉션 타입. |
| [map_t](./map_t/) | 기본 데이터 타입. |
| [this_t](./this_t/) | 현재 타입. |
| [Ptr](./ptr/) | 포인터 타입. |
| [KVPair](./kvpair/) | 키-값 쌍 타입. |
| [IEnumerablePtr](./ienumerableptr/) | 동일한 쌍의 컬렉션 타입. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** 타입. |
| [iterator](./iterator/) | 이터레이터 타입. |
| [const_iterator](./const_iterator/) | Const 이터레이터 타입. |
| [reverse_iterator](./reverse_iterator/) | 역방향 이터레이터 타입. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const 역방향 이터레이터 타입. |

## 참조

* 클래스 [SortedListHelper](../sortedlisthelper/)
* 클래스 [BaseDictionary](../basedictionary/)
* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)