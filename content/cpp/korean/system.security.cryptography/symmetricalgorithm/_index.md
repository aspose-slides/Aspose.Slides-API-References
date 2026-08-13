---
title: SymmetricAlgorithm
second_title: "Aspose.Slides for C++ API 레퍼런스"
description: "암호화와 복호화를 위해 동일한 키를 사용하는 대칭 알고리즘의 기본 클래스입니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해 인스턴스를 만들면 런타임 오류 및/또는 단언 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 651
url: /ko/system.security.cryptography/symmetricalgorithm/
---
## SymmetricAlgorithm 클래스

암호화와 복호화를 위해 동일한 키를 사용하는 대칭 알고리즘의 기본 클래스입니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 만들거나 operator new를 사용해 인스턴스를 생성하면 런타임 오류 및/또는 단언 실패가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오.

```cpp
class SymmetricAlgorithm : public virtual System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](./)\> [Create](./create/)(const [String](../../system/string/)\&) | 알고리즘 인스턴스를 생성합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | 알고리즘 객체와 연결된 매개변수로 복호화기를 생성합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 명시적 매개변수로 복호화기를 생성합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | 알고리즘 객체와 연결된 매개변수로 암호화기를 생성합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 명시적 매개변수로 암호화기를 생성합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 객체를 C# [Object.Equals](../../system/object/equals/) 의미로 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값(NaN 포함)과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값(NaN 포함)과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual void [GenerateIV](./generateiv/)() | 알고리즘을 위한 무작위 초기값을 생성합니다. 기존 값이 있으면 덮어씁니다. |
| virtual void [GenerateKey](./generatekey/)() | 알고리즘을 위한 무작위 키를 생성합니다. 기존 키가 있으면 덮어씁니다. |
| virtual int [get_BlockSize](./get_blocksize/)() | 암호화 작업의 블록 크기를 가져옵니다. |
| virtual int [get_FeedbackSize](./get_feedbacksize/)() | 암호화 작업의 피드백 크기를 가져옵니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](./get_iv/)() | 암호화 작업의 초기값을 가져옵니다. 아직 생성되지 않은 경우 새로 생성합니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](./get_key/)() | 암호화 작업의 키를 가져옵니다. 아직 생성되지 않은 경우 새로 생성합니다. |
| virtual int [get_KeySize](./get_keysize/)() | 암호화 작업의 키 크기를 가져옵니다. |
| virtual [CipherMode](../ciphermode/) [get_Mode](./get_mode/)() | 암호화 작업의 모드를 가져옵니다. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](./get_padding/)() | 암호화 작업의 패딩을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구정을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_BlockSize](./set_blocksize/)(int) | 암호화 작업의 블록 크기를 설정합니다. |
| virtual void [set_FeedbackSize](./set_feedbacksize/)(int) | 암호화 작업의 피드백 크기를 설정합니다. |
| virtual void [set_IV](./set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 암호화 작업의 초기값을 설정합니다. |
| virtual void [set_Key](./set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 암호화 작업의 키를 설정합니다. |
| virtual void [set_KeySize](./set_keysize/)(int) | 암호화 작업의 키 크기를 설정합니다. |
| virtual void [set_Mode](./set_mode/)([CipherMode](../ciphermode/)) | 암호화 작업의 모드를 설정합니다. |
| virtual void [set_Padding](./set_padding/)([PaddingMode](../paddingmode/)) | 암호화 작업의 패딩을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| **bool** [ValidKeySize](./validkeysize/)(int) | 키 크기가 유효한지 확인합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Security::Cryptography](../)
* 라이브러리 [Aspose.Slides](../../)