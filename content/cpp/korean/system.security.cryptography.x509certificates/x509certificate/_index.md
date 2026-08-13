---
title: X509Certificate
second_title: Aspose.Slides for C++ API 참조
description: "X.509 v.3 인증서. 암호화된 인증서는 지원되지 않습니다. X509KeyStorageFlags::DefaultKeySet 플래그만 지원됩니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 인스턴스를 만들거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 이 포인터를 함수 인자로 전달하십시오."
type: docs
weight: 27
url: /ko/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate 클래스

X.509 v.3 인증서. 암호화된 인증서는 지원되지 않습니다. [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) 플래그만 지원됩니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 이 포인터를 함수 인수로 전달하십시오.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## 메서드

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | 지정된 PKCS7 파일에서 인증서를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | 지정된 서명된 파일에서 인증서를 생성합니다. |
| void [Dispose](./dispose/)() override | 아무 것도 하지 않습니다. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | 두 인증서를 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | 지정된 형식을 사용하여 현재 객체를 바이트 배열로 내보냅니다. 구현되지 않음. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | 지정된 형식을 사용하여 현재 객체를 바이트 배열로 내보냅니다. 구현되지 않음. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | 지정된 형식을 사용하여 현재 객체를 바이트 배열로 내보냅니다. 구현되지 않음. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| IntPtr [get_Handle](./get_handle/)() const | Microsoft Cryptographic API 인증서 컨텍스트에 대한 핸들을 가져옵니다. |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | X.509v3 인증서를 발급한 인증 기관의 이름을 가져옵니다. |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | 인증서에서 주체 구분 이름을 가져옵니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | 현재 객체의 해시를 바이트 배열로 가져옵니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | 현재 객체의 해시를 바이트 배열로 가져옵니다. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | 현재 객체의 [SHA1](../../system.security.cryptography/sha1/) 해시를 16진수 문자열로 가져옵니다. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | 현재 객체의 [SHA1](../../system.security.cryptography/sha1/) 해시를 16진수 문자열로 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | 현재 인증서의 발효 날짜를 가져옵니다. |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | 현재 인증서의 만료 날짜를 가져옵니다. |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | 인증서 형식의 이름을 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 인증서 해시 코드를 가져옵니다. |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | 현재 인증서를 발급한 인증 기관의 이름을 가져옵니다. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | 현재 인증서의 키 정보를 문자열로 가져옵니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | 현재 인증서의 키 정보를 바이트 배열로 가져옵니다. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | 현재 인증서의 키 정보를 16진수 문자열로 가져옵니다. |
| virtual [String](../../system/string/) [GetName](./getname/)() const | 현재 인증서가 발급된 주체의 이름을 가져옵니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | 인증서에서 공개 키를 바이트 배열로 가져옵니다. |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | 인증서에서 공개 키를 16진수 문자열로 가져옵니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | 인증서에서 원시 데이터를 바이트 배열로 가져옵니다. |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | 인증서에서 원시 데이터를 16진수 문자열로 가져옵니다. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | 인증서에서 일련 번호를 바이트 배열로 가져옵니다. |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | 인증서에서 일련 번호를 16진수 문자열로 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 지정된 인증서 파일에서 정보를 가져옵니다. 구현되지 않음. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 지정된 인증서 파일에서 정보를 가져옵니다. 구현되지 않음. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 지정된 인증서 데이터에서 정보를 가져옵니다. 구현되지 않음. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 지정된 인증서 데이터에서 정보를 가져옵니다. 구현되지 않음. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | 지정된 인증서 파일에서 정보를 가져옵니다. 구현되지 않음. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 지정된 인증서 데이터에서 정보를 가져옵니다. 구현되지 않음. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로 아무것도 복사하지 않고, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 의해 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [Reset](./reset/)() | 인증서 상태를 재설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | 인증서 정보를 텍스트 형식으로 반환합니다. |
| [String](../../system/string/) [ToString](./tostring/)() const override | 인증서 정보를 텍스트 형식으로 반환합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터 또는 ThisProtector를 사용하십시오. |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | 생성자. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 생성자. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | 생성자. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | 포인터 유형. |

## 또 보기

* 클래스 [Object](../../system/object/)
* 클래스 [IDisposable](../../system/idisposable/)
* 네임스페이스 [System::Security::Cryptography::X509Certificates](../)
* 라이브러리 [Aspose.Slides](../../)