---
title: CspKeyContainerInfo
second_title: Aspose.Slides for C++ API 참조
description: 암호 키 쌍에 대한 추가 정보.
type: docs
weight: 66
url: /ko/system.security.cryptography/cspkeycontainerinfo/
---
## CspKeyContainerInfo 클래스

키 쌍에 대한 추가 정보.

```cpp
class CspKeyContainerInfo : public virtual System::Object
```

## 메서드

| Method | Description |
| --- | --- |
|  [CspKeyContainerInfo](./cspkeycontainerinfo/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | 생성자. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이트합니다. 두 NaN은 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 여기서는 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이트합니다. 두 NaN은 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 여기서는 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용. |
| **bool** [get_Accessible](./get_accessible/)() const | 컨테이너에 있는 키에 접근 가능한지 여부를 나타내는 플래그를 가져옵니다. |
| **bool** [get_Exportable](./get_exportable/)() const | 키를 컨테이너에서 내보낼 수 있는지 여부를 나타내는 플래그를 가져옵니다. |
| **bool** [get_HardwareDevice](./get_hardwaredevice/)() const | 키가 하드웨어 키인지 여부를 나타내는 플래그를 가져옵니다. |
| [String](../../system/string/) [get_KeyContainerName](./get_keycontainername/)() const | 키 컨테이너 이름을 가져옵니다. |
| [SharedPtr](../../system/sharedptr/)\<[KeyNumber](../keynumber/)\> [get_KeyNumber](./get_keynumber/)() const | KeyNumber 객체를 가져옵니다. |
| **bool** [get_MachineKeyStore](./get_machinekeystore/)() const | 키가 머신 키 저장소에서 로드되었는지 여부를 나타내는 플래그를 가져옵니다. |
| **bool** [get_Protected](./get_protected/)() const | 키가 복사로부터 보호되는지 여부를 나타내는 플래그를 가져옵니다. |
| [String](../../system/string/) [get_ProviderName](./get_providername/)() const | 제공자 이름을 가져옵니다. |
| **int32_t** [get_ProviderType](./get_providertype/)() const | 제공자 유형을 가져옵니다. |
| **bool** [get_RandomlyGenerated](./get_randomlygenerated/)() const | 키가 무작위로 생성되었는지 여부를 나타내는 플래그를 가져옵니다. |
| **bool** [get_Removable](./get_removable/)() const | 키를 컨테이너에서 제거할 수 있는지 여부를 나타내는 플래그를 가져옵니다. |
| [String](../../system/string/) [get_UniqueKeyContainerName](./get_uniquekeycontainername/)() const | 고유한 컨테이너 이름을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자입니다. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Security::Cryptography](../)
* 라이브러리 [Aspose.Slides](../../)