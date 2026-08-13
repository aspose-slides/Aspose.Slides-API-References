---
title: EnumeratorSelectManyAdapter
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 105
url: /ko/system.collections.generic.details/enumeratorselectmanyadapter/
---
## EnumeratorSelectManyAdapter 클래스

```cpp
template<typename Source,typename Result>class EnumeratorSelectManyAdapter : public System::Collections::Generic::IEnumerator<Result>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [IEnumerator](../../system.collections.generic/ienumerator/) * [AsVirtualizedIterator](../../system.collections.generic/ienumerator/asvirtualizediterator/)() | VirtualizedIterator 클래스에서 사용할 반복자를 준비합니다. |
| System::Details::VirtualizedIteratorBase\<Result\> * [CloneIterator](./cloneiterator/)() const override |  |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../../system.collections.generic/ienumerator/current/)() const | 현재 요소를 가져옵니다. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | 아무 작업도 하지 않습니다. |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/)([SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<Source\>\>, const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이션합니다. 두 NaN을 동일하게 간주합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않음). |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이션합니다. 두 NaN을 동일하게 간주합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않음). |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [MakeConstRef_t](../../system/makeconstref_t/)\<Result\> [get_Current](./get_current/)() const override | 현재 요소를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| [IEnumerator](../../system.collections.generic/ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../../system.collections.generic/ienumerator/incrementiterator/)() override | 반복자를 한 단계 앞으로 이동합니다. |
| void [InitializeIterator](../../system.collections.generic/ienumerator/initializeiterator/)() override | 첫 번째 [MoveNext()](../../system.collections.generic/ienumerator/movenext/) 호출을 수행하고 VirtualizedIterator에서 사용할 열거자 객체를 준비합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용합니다. |
| void [MarkOwnedByVirtualizedIterator](../../system.collections.generic/ienumerator/markownedbyvirtualizediterator/)() | 가상화된 반복자가 소유하는 열거자를 표시합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
| **bool** [MoveNext](./movenext/)() override | 열거자를 다음 요소로 이동합니다. 이전에 요소가 참조되지 않은 경우 첫 번째 사용 가능한 요소를 참조하도록 설정합니다. 컨테이너 끝에 도달하면 아무 작업도 하지 않습니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [Reset](./reset/)() override | 열거자를 첫 요소 앞 위치로 재설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자 객체를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual  [~IEnumerator](../../system.collections.generic/ienumerator/~ienumerator/)() |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [IEnumerator](../../system.collections.generic/ienumerator/)
* 네임스페이스 [System::Collections::Generic::Details](../)
* 라이브러리 [Aspose.Slides](../../)