---
title: RSACryptoServiceProvider
second_title: Aspose.Slides for C++ API 레퍼런스
description: "CSP 형태의 RSA 알고리즘. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 이 타입의 인스턴스를 스택에 생성하거나 operator new를 사용하지 마십시오. 그렇지 않으면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하십시오."
type: docs
weight: 469
url: /ko/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider 클래스

[RSA](../rsa/) 알고리즘 in CSP form. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당되어야 합니다. 이 타입의 인스턴스를 스택에 직접 만들거나 operator new를 사용하여 생성하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 래핑하고, 해당 포인터를 인수로 함수에 전달하십시오.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | 모든 자원을 해제합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)() | 기본 [RSA](../rsa/) 알고리즘 구현을 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [String](../../system/string/)\&) | 기본 [RSA](../rsa/) 알고리즘 구현을 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(**int32_t**) | 지정된 키 크기로 기본 [RSA](../rsa/) 알고리즘 구현을 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [RSAParameters](../rsaparameters/)\&) | 지정된 매개변수로 기본 [RSA](../rsa/) 알고리즘 구현을 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [CreateFromXmlString](../rsa/createfromxmlstring/)(const [String](../../system/string/)\&) | 지정된 XML 인코딩 매개변수로 기본 [RSA](../rsa/) 알고리즘 구현을 생성합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | 메시지를 복호화합니다. 구현되지 않음. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | 지정된 패딩 모드를 사용하여 입력 데이터를 복호화합니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [DecryptValue](../rsa/decryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | 개인 키를 사용하여 값을 복호화합니다. |
| void [Dispose](./dispose/)() override | 객체와 연관된 데이터를 해제합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | 메시지를 암호화합니다. 구현되지 않음. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | 지정된 패딩 모드를 사용하여 입력 데이터를 암호화합니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [EncryptValue](../rsa/encryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | 개인 키를 사용하여 값을 암호화합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | 키에 대한 정보를 포함한 블롭을 내보냅니다. 구현되지 않음. |
| [RSAParameters](../rsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | CSP 매개변수를 내보냅니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| void [FromXmlString](../rsa/fromxmlstring/)([String](../../system/string/)) override | XML 인코딩 매개변수를 사용하여 객체를 초기화합니다. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | [CspKeyContainerInfo](../cspkeycontainerinfo/) 객체를 가져옵니다. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | 객체와 연관된 키 교환 알고리즘을 확인합니다. |
| **int32_t** [get_KeySize](./get_keysize/)() override | 알고리즘에서 사용되는 키 크기를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | 허용된 키 크기 배열을 가져옵니다. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | 키가 CSP 객체에 영구 저장되는지 확인합니다. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | CSP 객체에 공개키만 존재하는지 확인합니다. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | CSP 객체와 연관된 서명 알고리즘을 가져옵니다. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | 키가 사용자 저장소가 아닌 머신 저장소에 영구 저장되는지 확인합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | 키에 대한 정보를 포함한 블롭을 가져옵니다. 구현되지 않음. |
| void [ImportParameters](./importparameters/)([RSAParameters](../rsaparameters/)) override | CSP 매개변수를 가져옵니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입을 복제할 수 있게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | 생성자. 기본 매개변수를 사용합니다. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | 생성자. 구현되지 않음. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [RSAParameters](../rsaparameters/)\&) | 생성자. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**) | 생성자. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | 생성자. 구현되지 않음. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | 키 크기를 설정합니다. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | 키가 CSP 객체에 영구 저장되는지 정의합니다. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | 키가 사용자 저장소가 아닌 머신 저장소에 영구 저장되는지 정의합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 강한 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 지정된 입력 값의 서명을 계산합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 지정된 입력 값의 서명을 계산합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | 지정된 입력 값의 서명을 계산합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | 지정된 해시 알고리즘과 패딩을 사용하여 지정된 데이터 배열의 해시 값을 계산하고 결과에 서명합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | 지정된 해시 알고리즘과 패딩을 사용하여 지정된 데이터 배열의 해시 값을 계산하고 결과에 서명합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | 지정된 해시 알고리즘과 패딩을 사용하여 지정된 바이너리 스트림의 해시 값을 계산하고 결과에 서명합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)([ByteArrayPtr](../../system/bytearrayptr/), [HashAlgorithmName](../hashalgorithmname/), [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | 지정된 해시 값에 대한 서명을 계산합니다. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | 지정된 입력 값의 서명을 계산합니다. 구현되지 않음. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| [String](../../system/string/) [ToXmlString](../rsa/toxmlstring/)(**bool**) override | 모든 매개변수를 XML 형식으로 내보냅니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 데이터 서명을 확인합니다. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | 지정된 데이터의 서명이 유효한지 검증합니다. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | 지정된 데이터의 서명이 유효한지 검증합니다. |
| **bool** [VerifyData](../rsa/verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | 지정된 바이너리 스트림의 서명이 유효한지 검증합니다. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 데이터 서명을 확인합니다. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/), const [HashAlgorithmName](../hashalgorithmname/)\&, [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | 지정된 해시의 서명이 유효한지 검증합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [RSA](../rsa/)
* 클래스 [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* 네임스페이스 [System::Security::Cryptography](../)
* 라이브러리 [Aspose.Slides](../../)