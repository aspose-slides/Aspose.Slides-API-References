---
title: ECDsaBotan
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Botan 형식의 ECDsa 알고리즘입니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 196
url: /ko/system.security.cryptography/ecdsabotan/
---
## ECDsaBotan 클래스

[ECDsa](../ecdsa/) 알고리즘을 Botan 형태로 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용해서 생성하지 말아야 하며, 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하십시오.

```cpp
class ECDsaBotan : public System::Security::Cryptography::ECDsa
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | 모든 리소스를 해제합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)() | 기본 ECDSA 알고리즘 구현을 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECCurve](../eccurve/)\&) | 지정된 곡선에 대해 새로 생성된 키를 사용하여 기본 ECDSA 알고리즘 구현을 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [ECParameters](../ecparameters/)\&) | 지정된 매개변수를 사용하여 기본 ECDSA 알고리즘 구현을 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](../ecdsa/)\> [Create](../ecdsa/create/)(const [String](../../system/string/)\&) | 지정된 ECDSA 알고리즘 구현을 생성합니다. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | 현재 객체가 소유한 리소스를 해제합니다. |
|  [ECDsaBotan](./ecdsabotan/)() | 생성자. 기본 매개변수를 사용합니다. |
|  [ECDsaBotan](./ecdsabotan/)(const [ECParameters](../ecparameters/)\&) | 생성자. |
|  [ECDsaBotan](./ecdsabotan/)(const [ECCurve](../eccurve/)\&) | 생성자. |
|  [ECDsaBotan](./ecdsabotan/)(**int32_t**) | 생성자. |
|  [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PublicKey\&) | 생성자. |
|  [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PrivateKey\&) | 생성자. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동 소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동 소수점 비교를 흉내내어 두 NaN을 동일하게 간주합니다. |
| [ECParameters](../ecparameters/) [ExportExplicitParameters](./exportexplicitparameters/)(**bool**) override | 명시적인 매개변수를 내보냅니다. |
| [ECParameters](../ecparameters/) [ExportParameters](./exportparameters/)(**bool**) override | 명명된 혹은 명시적인 매개변수를 내보냅니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | XML 인코딩된 매개변수를 사용하여 객체를 초기화합니다. 구현되지 않음. |
| void [FromXmlString](./fromxmlstring/)(const [String](../../system/string/)\&, [ECKeyXmlFormat](../eckeyxmlformat/)) | XML 인코딩된 매개변수를 사용하여 객체를 초기화합니다. 구현되지 않음. |
| void [GenerateKey](./generatekey/)(const [ECCurve](../eccurve/)\&) override | 지정된 곡선에 대한 새로운 공개/개인 키 쌍을 생성합니다. |
| [HashAlgorithmName](../hashalgorithmname/) [get_HashAlgorithm](./get_hashalgorithm/)() const | 해시 알고리즘을 가져옵니다. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](../ecdsa/get_keyexchangealgorithm/)() override | 사용할 키 교환 알고리즘을 가져옵니다. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | 키 크기를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | 허용된 키 크기 배열을 가져옵니다. |
| [String](../../system/string/) [get_SignatureAlgorithm](../ecdsa/get_signaturealgorithm/)() override | 사용할 서명 알고리즘을 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 동일합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 동일합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([ByteArrayPtr](../../system/bytearrayptr/), **int32_t**, **int32_t**, [HashAlgorithmName](../hashalgorithmname/)) override | 지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [HashData](./hashdata/)([StreamPtr](../../system/streamptr/), [HashAlgorithmName](../hashalgorithmname/)) override | 지정된 해시 알고리즘을 사용하여 지정된 바이너리 스트림의 해시 값을 계산합니다. |
| void [ImportParameters](./importparameters/)(const [ECParameters](../ecparameters/)\&) override | 데이터 구조에서 모든 매개변수를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 동일합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 동일합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_HashAlgorithm](./set_hashalgorithm/)(const [HashAlgorithmName](../hashalgorithmname/)\&) | 해시 알고리즘을 설정합니다. |
| void [set_KeySize](./set_keysize/)(**int32_t**) override | 키 크기를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 지정된 데이터 배열의 해시 값을 계산하고 결과에 서명합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | 지정된 데이터 배열의 해시 값을 계산하고 결과에 서명합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&) | 지정된 바이너리 스트림의 해시 값을 계산하고 결과에 서명합니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산하고 결과에 서명합니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | 지정된 해시 알고리즘을 사용하여 지정된 데이터 배열의 해시 값을 계산하고 결과에 서명합니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 지정된 해시 알고리즘을 사용하여 지정된 바이너리 스트림의 해시 값을 계산하고 결과에 서명합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | 지정된 입력 값의 서명을 계산합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 동일합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | XML 형식으로 모든 매개변수를 내보냅니다. 구현되지 않음. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)([ECKeyXmlFormat](../eckeyxmlformat/)) | XML 형식으로 모든 매개변수를 내보냅니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 지정된 데이터의 서명이 올바른지 검증합니다. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 지정된 데이터의 서명이 올바른지 검증합니다. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 지정된 바이너리 스트림의 서명이 올바른지 검증합니다. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 지정된 데이터의 서명이 올바른지 검증합니다. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 지정된 데이터의 서명이 올바른지 검증합니다. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | 지정된 바이너리 스트림의 서명이 올바른지 검증합니다. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | 데이터 서명을 확인합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ECDsa](../ecdsa/)
* 네임스페이스 [System::Security::Cryptography](../)
* 라이브러리 [Aspose.Slides](../../)