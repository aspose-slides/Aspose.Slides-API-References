---
title: List
second_title: Aspose.Slides for C++ API 레퍼런스
description: List 전방 선언.
type: docs
weight: 430
url: /ko/system.collections.generic/list/
---
## List 클래스


[List](./) 전방 선언.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 요소 유형. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++ 전용. |
| void [Add](./add/)(const T\&) override | 리스트 끝에 요소를 추가합니다. |
| void [AddInitializer](./addinitializer/)(int, const T *) | 리스트에 요소를 추가합니다; 초기화자를 변환할 때 사용됩니다. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | 컬렉션(또는 자체)에서 모든 요소를 현재 리스트의 끝에 추가합니다. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | 이 컬렉션에 대한 읽기 전용 참조를 가져옵니다. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | 컬렉션의 첫 번째 요소에 대한 반복자를 가져옵니다. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | const 한정 컬렉션의 첫 번째 요소에 대한 반복자를 가져옵니다. |
| int [BinarySearch](./binarysearch/)(const T\&) const | 정렬된 리스트에서 항목을 찾습니다. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | 정렬된 리스트에서 항목을 찾습니다. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | 정렬된 리스트에서 항목을 찾습니다. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | 컬렉션의 첫 번째 const 한정 요소에 대한 반복자를 가져옵니다. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | 컬렉션 끝 뒤에 존재하지 않는 const 한정 요소에 대한 반복자를 가져옵니다. |
| void [Clear](./clear/)() override | 모든 요소를 삭제합니다. |
| **bool** [Contains](./contains/)(const T\&) const override | 리스트에 항목이 존재하는지 확인합니다. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | 다른 유형으로 변환된 요소들의 리스트를 생성합니다. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | 리스트 요소를 기존 배열 요소에 복사합니다. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | 모든 요소를 기존 배열 요소에 복사합니다. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | 지정된 인덱스부터 시작하여 요소를 기존 배열 요소에 복사합니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 컬렉션의 마지막 const 한정 요소에 대한 역방향 반복자를 가져옵니다(역방향에서 첫 번째). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 컬렉션 시작 앞에 존재하지 않는 const 한정 요소에 대한 역방향 반복자를 가져옵니다. |
| [vector_t](./vector_t/)\& [data](./data/)() | 기본 데이터 구조 접근 함수. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | 기본 데이터 구조 접근 함수. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | 컬렉션 끝 뒤에 존재하지 않는 요소에 대한 반복자를 가져옵니다. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | const 한정 컬렉션 끝 뒤에 존재하지 않는 요소에 대한 반복자를 가져옵니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따라 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따라 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | 리스트에 특정 조건을 만족하는 요소가 존재하는지 확인합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | 특정 조건을 만족하는 요소를 찾습니다. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | 특정 조건을 만족하는 요소들을 찾습니다. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | 특정 조건을 만족하는 요소를 찾습니다. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | 특정 조건을 만족하는 요소를 찾습니다. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | 특정 조건을 만족하는 요소를 찾습니다. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | 특정 조건을 만족하는 마지막 요소를 찾습니다. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | 리스트의 모든 요소에 동작을 적용합니다. |
| int [get_Capacity](./get_capacity/)() const | 현재 리스트 용량을 가져옵니다. |
| int [get_Count](./get_count/)() const override | 현재 리스트의 요소 수를 가져옵니다. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | 컬렉션이 고정 크기인지 확인합니다. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | 컬렉션이 읽기 전용인지 확인합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | 컬렉션이 동기화되는 객체를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | 리스트 요소를 순회할 열거자를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | 리스트의 슬라이스를 생성합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
|  [ICollection](../icollection/icollection/)() | 기본 생성자. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | 복사 생성자. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | 이동 생성자. |
| T [idx_get](./idx_get/)(int) const override | 특정 위치의 요소를 가져옵니다. |
| void [idx_set](./idx_set/)(int, T) override | 특정 위치에 요소를 설정합니다. |
| int [IndexOf](./indexof/)(const T\&) const override | 특정 항목의 첫 번째 인덱스를 가져옵니다. |
| int [IndexOf](./indexof/)(const T\&, int) const | 리스트에서 특정 항목을 찾습니다. |
| void [Insert](./insert/)(int, const T\&) override | 지정된 위치에 항목을 삽입합니다. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | 특정 위치에 데이터 범위를 삽입합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | 지정된 객체를 검색하고 전체 리스트에서 마지막으로 나타나는 위치의 0부터 시작하는 인덱스를 반환합니다. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | 지정된 객체를 검색하고 [List](./)의 첫 번째 요소부터 지정된 인덱스까지의 범위 내에서 마지막으로 나타나는 위치의 0부터 시작하는 인덱스를 반환합니다. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | [List](./)에서 지정된 개수의 요소를 포함하고 지정된 인덱스에서 끝나는 범위 내에서 지정된 객체를 검색하고 마지막으로 나타나는 위치의 0부터 시작하는 인덱스를 반환합니다. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 시퀀스에 누적 함수를 적용합니다. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | 시퀀스의 모든 요소가 조건을 만족하는지 판단합니다. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | 시퀀스에 요소가 하나라도 포함되는지 판단합니다. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | 시퀀스에 요소가 존재하거나 조건을 만족하는지 판단합니다. |
| T [LINQ_Average](../ienumerable/linq_average/)() | 숫자 값 시퀀스의 평균을 계산합니다. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 입력 시퀀스의 각 요소에 변환 함수를 적용하여 얻은 값들의 평균을 계산합니다. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | 요소들을 지정된 유형으로 캐스팅합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | 두 시퀀스를 연결합니다. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | 시퀀스에 지정된 값이 포함되는지 판단합니다. |
| int [LINQ_Count](../ienumerable/linq_count/)() | 시퀀스의 요소 수를 반환합니다(직접 카운팅으로 계산). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 시퀀스에서 지정된 조건을 만족하는 요소 수를 반환합니다. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | 시퀀스에서 지정된 인덱스의 요소를 반환합니다. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | 시퀀스에서 지정된 인덱스의 요소를 반환합니다. |
| T [LINQ_First](../ienumerable/linq_first/)() | 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 시퀀스에서 지정된 조건을 만족하는 첫 번째 요소를 반환합니다. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | 시퀀스의 첫 번째 요소를 반환합니다. 시퀀스가 비어 있으면 기본값을 반환합니다. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 조건을 만족하는 시퀀스의 첫 번째 요소를 반환합니다. 해당 요소가 없으면 기본값을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 시퀀스의 요소들을 그룹화합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 시퀀스의 요소들을 그룹화합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | 시퀀스의 마지막 요소를 반환합니다. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | 시퀀스의 마지막 요소를 반환합니다. 시퀀스가 비어 있으면 기본값을 반환합니다. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 호출하고 최대 결과값을 반환합니다. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 호출하고 최소 결과값을 반환합니다. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | 지정된 유형에 따라 시퀀스의 요소를 필터링합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값에 따라 시퀀스 요소를 오름차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | keySelector가 선택한 키 값에 따라 시퀀스 요소를 내림차순으로 정렬합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | 시퀀스 요소의 순서를 뒤집습니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 시퀀스 요소를 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 요소의 인덱스를 포함하여 시퀀스의 각 요소를 새로운 형태로 변환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | 시퀀스의 각 요소를 투영하고 결과 시퀀스를 하나의 시퀀스로 결합합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | 시퀀스 시작부터 지정된 개수만큼 연속된 요소를 건너뛰고 나머지를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | 시퀀스 시작부터 지정된 개수의 연속된 요소를 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | 시퀀스에서 배열을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | 시퀀스에서 List<T>를 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | 지정된 조건에 따라 시퀀스를 필터링합니다. |
|  [List](./list/)() | 빈 리스트를 생성합니다. |
|  [List](./list/)(int) | 사전 정의된 용량을 가진 리스트를 생성합니다. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | 복사 생성자. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형을 복제할 수 있게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | 이동 대입 연산자. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | 이동 대입 연산자. |
| vector_t::reference [operator[]](./operator[]/)(int) | 접근자 함수. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | 접근자 함수. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 컬렉션의 마지막 요소에 대한 역방향 반복자를 가져옵니다(역방향에서 첫 번째). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | const 한정 컬렉션의 마지막 요소에 대한 역방향 반복자를 가져옵니다(역방향에서 첫 번째). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| **bool** [Remove](./remove/)(const T\&) override | 리스트에서 특정 항목의 첫 번째 인스턴스를 제거합니다. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | 특정 조건을 만족하는 모든 요소를 제거합니다. |
| void [RemoveAt](./removeat/)(int) override | 지정된 위치의 항목을 제거합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [RemoveRange](./removerange/)(int, int) | 리스트의 슬라이스를 제거합니다. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 컬렉션 시작 앞에 존재하지 않는 요소에 대한 역방향 반복자를 가져옵니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | const 한정 컬렉션 시작 앞에 존재하지 않는 요소에 대한 역방향 반복자를 가져옵니다. |
| void [Reverse](./reverse/)() | 전체 리스트의 요소 순서를 뒤집습니다. |
| void [Reverse](./reverse/)(int, int) | 리스트 슬라이스의 요소 순서를 뒤집습니다. |
| void [set_Capacity](./set_capacity/)(int) | 리스트 용량을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하세요. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | 리스트의 요소를 정렬합니다. |
| void [Sort](./sort/)() | 기본 비교자를 사용하여 리스트 요소를 정렬합니다. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | 리스트 슬라이스의 요소를 정렬합니다. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | 리스트의 요소를 정렬합니다. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | 리스트를 배열로 변환합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| void [TrimExcess](./trimexcess/)() | 리스트 용량을 크기에 맞게 조정합니다. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | 컬렉션의 모든 요소가 지정된 조건을 만족하는지 판단합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현하여 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 현재 컨테이너의 begin const 반복자 구현을 가져옵니다. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 현재 컨테이너의 begin 반복자 구현을 가져옵니다. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 현재 컨테이너의 end const 반복자 구현을 가져옵니다. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 현재 컨테이너의 end 반복자 구현을 가져옵니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하세요. |
| virtual  [~ICollection](../icollection/~icollection/)() | 소멸자. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입정의

| 타입정의 | 설명 |
| --- | --- |
| [ValueType](./valuetype/) | 이 타입. |
| [BaseType](./basetype/) | 인터페이스 타입. |
| [vector_t](./vector_t/) | 기본 데이터 타입. |
| [iterator](./iterator/) | 반복자 타입. |
| [const_iterator](./const_iterator/) | 상수 반복자 타입. |
| [reverse_iterator](./reverse_iterator/) | 역방향 반복자 타입. |
| [const_reverse_iterator](./const_reverse_iterator/) | 상수 역방향 반복자 타입. |
| [IEnumerablePtr](./ienumerableptr/) | 동일 유형의 요소를 보유하는 컨테이너. |
| [IEnumeratorPtr](./ienumeratorptr/) | **열거자** 타입. |

## 비고

[List](./) - 번역된 코드에서 사용되는 std::vector의 래퍼. Requires operator == to be impemented for element type. [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 이 클래스 객체를 할당해야 합니다. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인자로 함수에 전달하십시오.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // 첫 번째 리스트를 생성합니다.
  auto list1 = MakeObject<List<int>>();

  // 첫 번째 리스트를 채웁니다.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // 첫 번째 리스트를 정렬합니다.
  // 첫 번째 리스트 항목은 다음과 같습니다: {-5, 1, 3, 8}
  list1->Sort();

  // 인덱스 2의 항목을 제거합니다.
  // 첫 번째 리스트 항목은 다음과 같습니다: {-5, 1, 8}
  list1->RemoveAt(2);

  // 인덱스 1에 항목을 삽입합니다.
  // 첫 번째 리스트 항목은 다음과 같습니다: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // 두 번째 리스트를 생성합니다.
  auto list2 = MakeObject<List<int>>();

  // 두 번째 리스트를 채웁니다.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // 두 번째 리스트의 요소들을 첫 번째 리스트에 추가합니다.
  list1->AddRange(list2);

  // 첫 번째 리스트 항목을 출력합니다.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
- 5 15 1 8 10 20 30
*/
```

## 또한 보기

* 클래스 [Object](../../system/object/)
* 클래스 [IList](../ilist/)
* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)