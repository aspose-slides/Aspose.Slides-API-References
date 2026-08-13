---
title: BaseDictionary
second_title: Aspose.Slides for C++ API 레퍼런스
description: "다양한 사전 유사 데이터 구조(예: Dictionary, SortedDictionary)를 위한 공통 코드를 구현합니다. 컨테이너를 정의할 때 상속을 제외하고는 직접 사용해서는 안 됩니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 53
url: /ko/system.collections.generic/basedictionary/
---
## BaseDictionary 클래스

다양한 사전 유사 데이터 구조(예: [Dictionary](../dictionary/), [SortedDictionary](../sorteddictionary/))에 대한 공통 코드를 구현합니다. 컨테이너를 정의할 때 상속을 제외하고는 직접 사용해서는 안 됩니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수만을 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 그렇게 하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Map | 기본 맵 유형. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | C++ 전용. |
| void [Add](./add/)(const key_t\&, const mapped_t\&) override | 키-값 쌍을 사전에 추가합니다. |
| [BaseDictionary](./basedictionary/)() | 빈 데이터 구조를 생성합니다. |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | 기본 맵 생성자에 인수를 전달하는 포워딩 생성자입니다. |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *, const Args\&...) | 복사 생성자. |
| [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *) | 복사 생성자. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | 컨테이너의 키-값 요소에 대한 KVPair 래퍼 iterator를 반환합니다. C# 스타일로 구현되었으며, iterator는 get_Key() 및 get_Value() 인터페이스를 가진 KVPair 객체를 반환해야 합니다. 컨테이너가 비어 있으면 반환된 iterator는 [end()](../ienumerable/end/)와 같습니다. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | 컬렉션(있는 경우)의 첫 번째 요소를 가리키는 iterator를 가져옵니다. 이 iterator는 [GetEnumerator()](../ienumerable/getenumerator/)가 T의 복사 객체를 반환하기 때문에 참조된 객체를 변경할 수 없습니다. |
| stl_const_iterator [cbegin](./cbegin/)() const | 컨테이너의 첫 번째 요소에 대한 iterator를 반환합니다. STL 스타일로 구현되었습니다. 컨테이너가 비어 있으면 반환된 iterator는 [end()](../ienumerable/end/)와 같습니다. |
| stl_const_iterator [cend](./cend/)() const | 컨테이너의 마지막 요소 다음 요소에 대한 iterator를 반환합니다. STL 스타일로 구현되었습니다. 이 요소는 자리표시자 역할을 하며, 접근을 시도하면 정의되지 않은 동작이 발생합니다. |
| void [Clear](./clear/)() override | 모든 요소를 삭제합니다. |
| **bool** [ContainsKey](./containskey/)(const key_t\&) const override | 키가 사전에 존재하는지 확인합니다. |
| **bool** [ContainsValue](./containsvalue/)(const mapped_t\&) | 값이 사전에 존재하는지 확인합니다. 값을 비교하기 위해 operator == 를 사용합니다. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | 사전 내용을 기존 배열 요소에 복사합니다. |
| Map\& [data](./data/)() | 기본 데이터 저장소 액세서. |
| const Map\& [data](./data/)() const | 기본 데이터 저장소 액세서. |
| [const_iterator](./const_iterator/) [end](./end/)() const | 컨테이너의 마지막 요소 다음에 있는 키-값 요소에 대한 KVPair 래퍼 iterator를 반환합니다. C# 스타일로 구현되었으며, iterator는 get_Key() 및 get_Value() 인터페이스를 가진 KVPair 객체를 반환해야 합니다. 이 요소는 자리표시자 역할을 하며, 접근을 시도하면 정의되지 않은 동작이 발생합니다. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | 컬렉션(있는 경우)의 마지막 요소 바로 뒤를 가리키는 iterator를 가져옵니다. 이 iterator는 [GetEnumerator()](../ienumerable/getenumerator/)가 T의 복사 객체를 반환하기 때문에 참조된 객체를 변경할 수 없습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값(그 자체 포함)과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값(그 자체 포함)과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| **int32_t** [get_Count](./get_count/)() const override | 요소 개수를 가져옵니다. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | 컬렉션 크기가 고정되어 있는지 확인합니다. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 컬렉션이 읽기 전용인지 확인합니다. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | 컨테이너가 스레드 안전한지 확인합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | 키 컬렉션에 접근합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | 컬렉션이 동기화되는 객체를 가져옵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | 값 컬렉션에 접근합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[KeyValuePair](../keyvaluepair/)\<key_t, mapped_t\>\>\> [GetEnumerator](./getenumerator/)() | 열거자 인스턴스를 생성합니다. 서브클래스에서 구현해야 합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | 찾으면 값을 반환하고, 그렇지 않으면 **Value()** 를 반환합니다. |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | 찾으면 값을 반환하고, 그렇지 않으면 **defaultValue** 를 반환합니다. |
| mapped_t [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | 찾으면 값을 반환하고, 그렇지 않으면 **null** 을 반환합니다. 참조 타입에만 의미가 있습니다. |
| [ICollection](../icollection/icollection/)() | 기본 생성자. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | 복사 생성자. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | 이동 생성자. |
| mapped_t [idx_get](./idx_get/)(const key_t\&) const override | 키 기반 getter 함수. |
| void [idx_set](./idx_set/)(const key_t\&, mapped_t) override | 키 기반 setter 함수. 요소를 변경하거나 생성합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 시퀀스에 누산기 함수를 적용합니다. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | 시퀀스의 모든 요소가 조건을 만족하는지 판단합니다. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 시퀀스에 요소가 하나라도 포함되는지 판단합니다. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | 시퀀스의 요소 중 하나라도 존재하거나 조건을 만족하는지 판단합니다. |
| T [LINQ_Average](../ienumerable/linq_average/)() | 수치값 시퀀스의 평균을 계산합니다. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 입력 시퀀스 각 요소에 변환 함수를 적용하여 얻은 값들의 평균을 계산합니다. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 요소를 지정된 타입으로 캐스팅합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 두 시퀀스를 연결합니다. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 시퀀스에 특정 값이 포함되는지 판단합니다. |
| int [LINQ_Count](../ienumerable/linq_count/)() | 시퀀스의 요소 개수를 반환합니다(직접 카운팅을 통해 계산). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스 요소 개수를 반환합니다. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 시퀀스에서 지정된 인덱스의 요소를 반환합니다. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 시퀀스에서 지정된 인덱스의 요소를 반환합니다. |
| T [LINQ_First](../ienumerable/linq_first/)() | 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 시퀀스의 첫 번째 요소를 반환하거나, 시퀀스가 비어 있으면 기본 값을 반환합니다. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 조건을 만족하는 시퀀스의 첫 번째 요소를 반환하거나, 해당 요소가 없으면 기본 값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 시퀀스의 요소들을 그룹화합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 시퀀스의 요소들을 그룹화합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 시퀀스의 마지막 요소를 반환합니다. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 시퀀스의 마지막 요소를 반환하거나, 시퀀스가 비어 있으면 기본 값을 반환합니다. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 적용하고 최대 결과 값을 반환합니다. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 적용하고 최소 결과 값을 반환합니다. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 지정된 타입을 기준으로 시퀀스의 요소들을 필터링합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값을 기준으로 시퀀스의 요소를 오름차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값을 기준으로 시퀀스의 요소를 내림차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 시퀀스의 요소 순서를 반전시킵니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 시퀀스의 요소들을 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 요소의 인덱스를 포함하여 시퀀스의 각 요소를 새로운 형태로 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | 시퀀스의 각 요소를 투영하고 결과 시퀀스를 하나의 시퀀스로 결합합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | 시퀀스 시작부터 지정된 개수만큼 연속된 요소를 건너뛰고 나머지를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 시퀀스 시작부터 지정된 개수의 연속된 요소를 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 시퀀스로부터 배열을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | 시퀀스로부터 List<T>를 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 지정된 프레디케이트에 따라 시퀀스를 필터링합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | 이동 할당 연산자. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | 이동 할당 연산자. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| virtual mapped_t\& [operator[]](./operator[]/)(const key_t\&) | Accessor 함수. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 의 문자열 경우에 대한 특수화. |
| **bool** [Remove](./remove/)(const key_t\&) override | 사전에서 특정 키를 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 강한 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| **bool** [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | 키값을 찾아서 존재하면 반환합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 언락을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 현재 컨테이너의 begin const iterator 구현을 가져옵니다. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 현재 컨테이너의 begin iterator 구현을 가져옵니다. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 현재 컨테이너의 end const iterator 구현을 가져옵니다. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 현재 컨테이너의 end iterator 구현을 가져옵니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~ICollection](../icollection/~icollection/)() | 소멸자. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 별칭 | 설명 |
| --- | --- |
| [map_t](./map_t/) | 내부 맵 타입. |
| [KeyCollection](./keycollection/) | 기본 저장소 타입에 맞는 올바른 할당자를 사용하도록 합니다. |
| [ValueCollection](./valuecollection/) | 값들의 컬렉션. |
| [KVPair](./kvpair/) | 키-값 쌍 타입. |
| [BaseType](./basetype/) | 구현된 인터페이스. |
| [iterator](./iterator/) | Iterator 타입. |
| [const_iterator](./const_iterator/) | Const iterator 타입. |

## 참고

* 클래스 [IDictionary](../idictionary/)
* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)