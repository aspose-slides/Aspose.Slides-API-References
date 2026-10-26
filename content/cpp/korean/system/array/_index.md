---
title: Array
second_title: Aspose.Slides for C++ API 레퍼런스
description: "배열 데이터 구조를 나타내는 클래스입니다. 이 클래스의 객체는 System::MakeArray() 및 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달해서 사용하십시오."
type: docs
weight: 14
url: /ko/system/array/
---
## Array 클래스

배열 데이터 구조를 나타내는 클래스입니다. 이 클래스의 객체는 [System::MakeArray()](../makearray/)와 [System::MakeObject()](../makeobject/) 함수를 사용하여 할당해야 합니다. 이 타입의 인스턴스를 스택에 생성하거나 operator new를 사용해서는 안 됩니다. 그렇게 하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달해야 합니다.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 배열 요소의 타입 |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [Add](./add/)(const T&) override | 현재 객체가 나타내는 배열이 읽기 전용이기 때문에 지원되지 않습니다. |
| [Array](./array/)() | 빈 배열을 생성합니다. |
| [Array](./array/)(int, const T&) | 채우기 생성자. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | 채우기 생성자. |
| [Array](./array/)(int, const T) | 채우기 생성자. |
| [Array](./array/)(**vector_t**&&) | 이동 생성자. |
| [Array](./array/)(const **vector_t**&) | 복사 생성자. |
| [Array](./array/)(const std::vector\<Q\>&) | [Array](./) 객체를 생성하고, **T**와 동일하지만 **UnderlyingType**와 다른 타입의 값을 가진 std::vector 객체에서 복사한 값으로 채웁니다. |
| [Array](./array/)(std::vector\<Q\>&&) | [Array](./) 객체를 생성하고, **T**와 동일하지만 **UnderlyingType**와 다른 타입의 값을 가진 std::vector 객체에서 이동된 값으로 채웁니다. |
| [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | [Array](./) 객체를 생성하고, **UnderlyingType** 타입의 요소를 포함하는 지정된 초기화 목록에서 값을 채웁니다. |
| [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>&) | [Array](./) 객체를 생성하고, **UnderlyingType** 타입의 요소를 포함하는 지정된 배열에서 값을 채웁니다. |
| [Array](./array/)(std::initializer_list\<**bool**\>, int) | [Array](./) 객체를 생성하고, bool 타입 요소를 포함하는 지정된 초기화 목록에서 값을 채웁니다. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | 배열을 읽기 전용 컬렉션으로 캐스팅합니다. |
| [iterator](./iterator/) [begin](./begin/)() | 컨테이너의 첫 번째 요소에 대한 반복자를 반환합니다. 컨테이너가 비어 있으면 반환된 반복자는 [end()](./end/)와 같습니다. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | const 한정 컨테이너의 첫 번째 요소에 대한 반복자를 반환합니다. 컨테이너가 비어 있으면 반환된 반복자는 [end()](./end/)와 같습니다. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T&) | 정렬된 배열에서 이진 검색을 수행합니다. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NOT IMPLEMENTED. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | const 한정 컨테이너의 첫 번째 요소에 대한 반복자를 반환합니다. 컨테이너가 비어 있으면 반환된 반복자는 [cend()](./cend/)와 같습니다. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | 컨테이너의 마지막 요소 다음 요소에 대한 반복자를 반환합니다. 이 요소는 플레이스홀더 역할을 하며, 접근하려고 하면 정의되지 않은 동작이 발생합니다. |
| void [Clear](./clear/)() override | 현재 객체가 나타내는 배열이 읽기 전용이기 때문에 지원되지 않습니다. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 지정된 배열에서 **startIndex** 인덱스부터 시작하여 **count**개의 값을 기본값으로 교체합니다. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | 배열을 복제합니다. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 지정된 소스에서 시작하여 [System.Array](./)의 요소 범위를 복사합니다. |
| **bool** [Contains](./contains/)(const T&) const override | 지정된 항목이 배열에 있는지 여부를 판단합니다. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | 지정된 변환자 대리자를 사용하여 **OutputType** 타입으로 변환된 지정된 배열의 요소로 새로운 [Array](./) 객체를 생성하고 채웁니다. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)\>) | 지정된 변환 함수 객체를 사용하여 **OutputType** 타입으로 변환된 지정된 배열의 요소로 새로운 [Array](./) 객체를 생성하고 채웁니다. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 지정된 수만큼의 요소를 소스 배열에서 대상 배열로 복사합니다. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 지정된 수만큼의 요소를 소스 배열 뷰에서 대상 배열로 복사합니다. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | 지정된 수만큼의 요소를 소스 배열에서 대상 배열 뷰로 복사합니다. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | 지정된 수만큼의 요소를 소스 배열 뷰에서 대상 배열 뷰로 복사합니다. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | 스택에 있는 소스 배열에서 지정된 수만큼의 요소를 대상 배열로 복사합니다. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | 지정된 수만큼의 요소를 소스 배열에서 스택에 있는 대상 배열로 복사합니다. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | 스택에 있는 소스 배열에서 지정된 수만큼의 요소를 스택에 있는 대상 배열로 복사합니다. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 지정된 인덱스에서 시작하여 소스 배열의 지정된 수만큼의 요소를 대상 배열의 지정된 위치에 복사합니다. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 지정된 인덱스에서 시작하여 소스 배열 뷰의 지정된 수만큼의 요소를 대상 배열의 지정된 위치에 복사합니다. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | 지정된 인덱스에서 시작하여 소스 배열의 지정된 수만큼의 요소를 대상 배열 뷰의 지정된 위치에 복사합니다. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | 지정된 인덱스에서 시작하여 소스 배열 뷰의 지정된 수만큼의 요소를 대상 배열 뷰의 지정된 위치에 복사합니다. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | 스택에 있는 소스 배열에서 지정된 인덱스부터 시작하여 지정된 수만큼의 요소를 대상 배열에 복사합니다. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | 지정된 인덱스에서 시작하여 소스 배열의 지정된 수만큼의 요소를 스택에 있는 대상 배열의 지정된 위치에 복사합니다. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | 스택에 있는 소스 배열에서 지정된 인덱스부터 시작하여 지정된 수만큼의 요소를 스택에 있는 대상 배열의 지정된 위치에 복사합니다. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | 지정된 인덱스에서 시작하여 소스 배열 뷰의 지정된 수만큼의 요소를 스택에 있는 대상 배열의 지정된 위치에 복사합니다. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | 현재 배열의 모든 요소를 지정된 대상 배열에 복사합니다. 요소는 arrayIndex 인수로 지정된 인덱스부터 대상 배열에 삽입됩니다. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | 현재 배열의 모든 요소를 지정된 대상 배열에 복사합니다. 요소는 dstIndex 인수로 지정된 인덱스부터 대상 배열에 삽입됩니다. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | 현재 배열의 모든 요소를 지정된 대상 배열 뷰에 복사합니다. 요소는 dstIndex 인수로 지정된 인덱스부터 대상 배열 뷰에 삽입됩니다. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | 현재 배열의 지정된 위치에서 시작하여 지정된 수만큼의 요소를 지정된 대상 배열에 복사합니다. 요소는 dstIndex 인수로 지정된 인덱스부터 대상 배열에 삽입됩니다. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | 현재 배열의 지정된 위치에서 시작하여 지정된 수만큼의 요소를 지정된 대상 배열 뷰에 복사합니다. 요소는 dstIndex 인수로 지정된 인덱스부터 대상 배열 뷰에 삽입됩니다. |
| int [Count](./count/)() const | 배열의 모든 차원에 있는 모든 요소의 총 개수를 나타내는 숫자를 반환합니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | 역순 컨테이너의 첫 번째 요소에 대한 역방향 반복자를 반환합니다. 이는 역순이 아닌 컨테이너의 마지막 요소에 해당합니다. 컨테이너가 비어 있으면 반환된 반복자는 [crend()](./crend/)와 같습니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | 역순 컨테이너의 마지막 요소 다음에 있는 역방향 반복자를 반환합니다. 이는 역순이 아닌 컨테이너의 첫 번째 요소 이전에 해당합니다. 이 요소는 플레이스홀더 역할을 하며, 접근하려고 하면 정의되지 않은 동작이 발생합니다. |
| **vector_t**& [data](./data/)() | 배열 요소를 저장하는 내부 데이터 구조에 대한 참조를 반환합니다. |
| const **vector_t**& [data](./data/)() const | 배열 요소를 저장하는 내부 데이터 구조에 대한 상수 참조를 반환합니다. |
| vector_t::pointer [data_ptr](./data_ptr/)() | 배열 요소가 저장되는 메모리 버퍼 시작부에 대한 원시 포인터를 반환합니다. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | 배열 요소가 저장되는 메모리 버퍼 시작부에 대한 상수 원시 포인터를 반환합니다. |
| [iterator](./iterator/) [end](./end/)() | 컨테이너의 마지막 요소 다음 요소에 대한 반복자를 반환합니다. 이 요소는 플레이스홀더 역할을 하며, 접근하려고 하면 정의되지 않은 동작이 발생합니다. |
| [const_iterator](./const_iterator/) [end](./end/)() const | const 한정 컨테이너의 마지막 요소 다음 요소에 대한 반복자를 반환합니다. 이 요소는 플레이스홀더 역할을 하며, 접근하려고 하면 정의되지 않은 동작이 발생합니다. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const&, T2 const&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const&, T2 const&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../object/equals/)(**float** const&, **float** const&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C# 스타일의 부동 소수점 비교를 에뮬레이트합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도(심지어 NaN과도) 같지 않지만, 여기서는 두 NaN을 동일하게 간주합니다. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | 지정된 [Array](./) 객체에 지정된 술어의 요구 조건을 만족하는 요소가 포함되어 있는지 결정합니다. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 지정된 배열에서 지정된 술어의 조건을 만족하는 첫 번째 요소를 검색합니다. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 지정된 술어에 의해 정의된 조건과 일치하는 모든 요소를 검색합니다. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 지정된 배열에서 지정된 술어의 조건을 만족하는 첫 번째 요소를 검색합니다. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | 지정된 배열의 각 요소에 지정된 작업을 수행합니다. |
| int [get_Count](./get_count/)() const override | 배열의 크기를 반환합니다. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | 컬렉션이 고정 크기인지 확인합니다. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | 배열이 읽기 전용인지 나타냅니다. |
| **int32_t** [get_Length](./get_length/)() const override | 배열의 모든 차원에 있는 모든 요소의 총 개수를 나타내는 32비트 정수를 반환합니다. |
| **int64_t** [get_LongLength](./get_longlength/)() const | 배열의 모든 차원에 있는 모든 요소의 총 개수를 나타내는 64비트 정수를 반환합니다. |
| **int32_t** [get_Rank](./get_rank/)() const | 구현되지 않음. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | 컬렉션이 동기화되는 객체를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | **Enumerator** 객체에 대한 포인터를 반환합니다. 이 객체는 현재 객체가 나타내는 배열의 요소에 대해 IEnumerator 인터페이스를 제공합니다. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| int [GetLength](./getlength/)(int) | 지정된 차원의 요소 개수를 반환합니다. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | 지정된 차원의 요소 개수를 64비트 정수로 반환합니다. |
| int [GetLowerBound](./getlowerbound/)(int) const | 지정된 차원의 하한을 반환합니다. |
| size_t [GetSizeTLength](./getsizetlength/)() const | 배열의 모든 차원에 있는 모든 요소의 총 개수를 나타내는 std::size_t 변수를 반환합니다. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../object/gettype/) 호출과 유사합니다. |
| int [GetUpperBound](./getupperbound/)(int) | 지정된 차원의 상한을 반환합니다. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | 기본 생성자. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | 복사 생성자. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | 이동 생성자. |
| T [idx_get](./idx_get/)(int) const override | 지정된 인덱스에 있는 항목을 반환합니다. |
| void [idx_set](./idx_set/)(int, T) override | 지정된 인덱스에 있는 배열 항목에 지정된 값을 설정합니다. |
| int [IndexOf](./indexof/)(const T\&) const override | 배열에서 지정된 항목이 처음 등장하는 인덱스를 결정합니다. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | 배열에서 지정된 항목이 처음 등장하는 인덱스를 결정합니다. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | 지정된 인덱스부터 시작하여 배열에서 지정된 항목이 처음 등장하는 인덱스를 결정합니다. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | 시작 인덱스와 범위 내 요소 수로 지정된 배열의 해당 범위에서 지정된 항목이 처음 등장하는 인덱스를 결정합니다. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | 현재 객체가 나타내는 배열을 지정된 배열의 값으로 채웁니다. |
| void [Initialize](./initialize/)() | 배열을 **T** 유형의 기본 생성 객체로 채웁니다. |
| void [Insert](./insert/)(int, const T\&) override | 현재 객체가 나타내는 배열이 읽기 전용이므로 지원되지 않습니다. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | 시작 인덱스와 범위 내 요소 수로 지정된 배열의 해당 범위에서 지정된 항목이 마지막으로 등장하는 인덱스를 결정합니다. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | 지정된 인덱스부터 시작하여 배열에서 지정된 항목이 마지막으로 등장하는 인덱스를 결정합니다. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | 배열에서 지정된 항목이 마지막으로 등장하는 인덱스를 결정합니다. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | 시퀀스에 누산기 함수를 적용합니다. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 시퀀스의 모든 요소가 조건을 만족하는지 결정합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 시퀀스에 요소가 하나라도 포함되어 있는지 결정합니다. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 시퀀스의 어떤 요소가 존재하거나 조건을 만족하는지 결정합니다. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 수치 값 시퀀스의 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | 입력 시퀀스의 각 요소에 변환 함수를 호출하고 평균을 계산합니다. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 요소들을 지정된 유형으로 캐스팅합니다. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 두 시퀀스를 연결합니다. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 시퀀스에 지정된 값이 포함되어 있는지 결정합니다. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 시퀀스의 요소 개수를 반환합니다(직접 카운팅을 통해 계산). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스 요소의 개수를 반환합니다. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 시퀀스에서 지정된 인덱스에 있는 요소를 반환합니다. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 시퀀스에서 지정된 인덱스에 있는 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | 지정된 조건을 만족하는 시퀀스의 첫 번째 요소를 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 시퀀스의 첫 번째 요소를 반환하며, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 조건을 만족하는 시퀀스의 첫 번째 요소를 반환하고, 해당 요소가 없으면 기본값을 반환합니다. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | 시퀀스의 요소들을 그룹화합니다. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | 시퀀스의 요소들을 그룹화합니다. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 시퀀스의 마지막 요소를 반환합니다. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 시퀀스의 마지막 요소를 반환하며, 시퀀스가 비어 있으면 기본값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | 일관된 시퀀스의 각 요소에 변환 함수를 호출하고 최대 결과값을 반환합니다. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | 일반 시퀀스의 각 요소에 변환 함수를 호출하고 최소 결과값을 반환합니다. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 지정된 유형에 따라 시퀀스의 요소들을 필터링합니다. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | keySelector에 의해 선택된 키 값에 따라 시퀀스의 요소들을 오름차순으로 정렬합니다. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | keySelector에 의해 선택된 키 값에 따라 시퀀스의 요소들을 내림차순으로 정렬합니다. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 시퀀스의 요소 순서를 뒤집습니다. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | 시퀀스의 요소들을 변환합니다. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | 요소의 인덱스를 포함하여 시퀀스의 각 요소를 새로운 형태로 변환합니다. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 시퀀스의 각 요소를 투영하고 결과 시퀀스를 하나의 시퀀스로 결합합니다. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 시퀀스 시작부터 지정된 수만큼 연속 요소를 건너뛰고 나머지를 반환합니다. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 시퀀스 시작부터 지정된 수만큼 연속된 요소들을 반환합니다. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 시퀀스로부터 배열을 생성합니다. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 시퀀스로부터 List<T>를 생성합니다. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 지정된 술어에 따라 시퀀스를 필터링합니다. |
| void [Lock](../object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용합니다. |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | [operator<()](../operator_less/)를 사용하여 요소를 비교하여 배열에서 가장 큰 요소를 찾습니다. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | [operator<()](../operator_less/)를 사용하여 요소를 비교하여 배열에서 가장 작은 요소를 찾습니다. |
|  [Object](../object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../object/object/)([Object](../object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | 이동 대입 연산자. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | 이동 대입 연산자. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | 지정된 인덱스에 있는 항목을 반환합니다. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | 지정된 인덱스에 있는 항목을 반환합니다. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | 단일 차원 배열의 첫 번째 요소에 대한 포인터를 반환합니다. 다차원 배열의 경우 결과는 정의되지 않습니다. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | 뒤집힌 컨테이너의 첫 번째 요소에 대한 역방향 반복자를 반환합니다. 이는 뒤집히지 않은 컨테이너의 마지막 요소에 해당합니다. 컨테이너가 비어 있으면 반환된 반복자는 [rend()](./rend/)와 같습니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | 역전된 컨테이너의 첫 번째 요소에 대한 역방향 반복자를 반환합니다. 이는 비역전된 컨테이너의 마지막 요소에 해당합니다. 컨테이너가 비어 있는 경우, 반환된 반복자는 [rend()](./rend/)와 같습니다. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)에 대한 문자열과 nullptr 경우의 특수화. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)에 대한 문자열 경우의 특수화. |
| **bool** [Remove](./remove/)(const T\&) override | 현재 객체가 나타내는 배열이 읽기 전용이므로 지원되지 않습니다. |
| void [RemoveAt](./removeat/)(int) override | 현재 객체가 나타내는 배열이 읽기 전용이므로 지원되지 않습니다. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | 역전된 컨테이너의 마지막 요소 다음 요소에 대한 역방향 반복자를 반환합니다. 이는 비역전된 컨테이너의 첫 번째 요소 이전 요소에 해당합니다. 이 요소는 자리 표시자이며, 접근하려고 하면 정의되지 않은 동작이 발생합니다. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | 역전된 컨테이너의 마지막 요소 다음 요소에 대한 역방향 반복자를 반환합니다. 이는 비역전된 컨테이너의 첫 번째 요소 이전 요소에 해당합니다. 이 요소는 자리 표시자이며, 접근하려고 하면 정의되지 않은 동작이 발생합니다. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | 지정된 배열의 크기를 지정된 값으로 변경하거나 지정된 크기의 새 배열을 생성합니다. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | 지정된 배열의 요소를 역순으로 정렬합니다. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 지정된 배열의 요소 범위를 역순으로 정렬합니다. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | 배열이 저장된 포인터를 약한 참조(가능한 경우)로 처리하도록 합니다. |
| void [SetValue](./setvalue/)(const T\&, int) | 지정된 인덱스의 요소 값을 설정합니다. |
| int [SharedCount](../object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | 기본 비교자를 사용하여 지정된 배열의 요소를 정렬합니다. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | 기본 비교자를 사용하여 지정된 배열의 요소 범위를 정렬합니다. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | 지정된 비교자를 사용하여 지정된 배열의 요소를 정렬합니다. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | 구현되지 않음. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | 지정된 비교를 사용하여 지정된 배열의 요소를 정렬합니다. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | 키를 포함하는 배열과 해당 항목을 포함하는 배열 두 개를 정렬합니다. 키 배열의 값에 따라 정렬되며, 요소는 operator<를 사용하여 비교됩니다. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | 키를 포함하는 배열과 해당 항목을 포함하는 배열 두 개를 정렬합니다. 키 배열의 값에 따라 정렬되며, 요소는 기본 비교자를 사용하여 비교됩니다. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | C# [Object.ToString()](../object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | 지정된 배열의 모든 요소가 지정된 프레디케이트가 정의한 조건을 만족하는지 여부를 결정합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) 구문을 구현합니다. |
| void [Unlock](../object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../lockcontext/) 감시 객체를 사용하십시오. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | 현재 컨테이너에 대한 begin const 반복자 구현을 가져옵니다. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | 현재 컨테이너에 대한 begin 반복자 구현을 가져옵니다. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | 현재 컨테이너에 대한 end const 반복자 구현을 가져옵니다. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | 현재 컨테이너에 대한 end 반복자 구현을 가져옵니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | 소멸자. |
| virtual  [~Object](../object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 별칭 | 설명 |
| --- | --- |
| [ValueType](./valuetype/) | 배열 요소 유형에 대한 별칭입니다. |
| [UnderlyingType](./underlyingtype/) | 배열의 각 요소를 나타내는 데 사용되는 유형에 대한 별칭입니다. |
| [EnumerablePtr](./enumerableptr/) | **T** 유형의 요소를 포함하는 IEnumerable 객체를 가리키는 공유 포인터 타입에 대한 별칭입니다. |
| [EnumeratorPtr](./enumeratorptr/) | **T** 유형의 요소를 포함하는 IEnumerator 객체를 가리키는 공유 포인터 타입에 대한 별칭입니다. |
| [iterator](./iterator/) | 반복자 유형. |
| [const_iterator](./const_iterator/) | 상수 반복자 유형. |
| [reverse_iterator](./reverse_iterator/) | 역방향 반복자 유형. |
| [const_reverse_iterator](./const_reverse_iterator/) | 상수 역방향 반복자 유형. |

## 비고



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // 배열을 생성하고 채웁니다.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // 배열 항목을 출력합니다.
  Print(arrayPtr);

  // 배열 항목을 오름차순으로 정렬합니다.
  Array<int32_t>::Sort(arrayPtr);

  // 배열 항목을 출력합니다.
  Print(arrayPtr);

  // 배열 항목의 개수를 출력합니다.
  std::cout << arrayPtr->get_Length() << std::endl;

  // 값이 4와 같은 항목의 인덱스를 출력합니다.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // 배열의 크기를 조정합니다.
  Array<int32_t>::Resize(arrayPtr, 3);

  // 배열 항목을 출력합니다.
  Print(arrayPtr);

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## 참조

* 클래스 [ArrayBase](../arraybase/)
* 클래스 [IList](../../system.collections.generic/ilist/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)