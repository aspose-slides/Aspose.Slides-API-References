---
title: ProtectionManager
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션 비밀번호 보호 관리.
type: docs
weight: 4915
url: /ko/aspose.slides/protectionmanager/
---
## ProtectionManager 클래스

[Presentation](../presentation/) 비밀번호 보호 관리.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | 프레젠테이션이 수정하기 위해 비밀번호로 보호되는지 여부를 결정합니다. |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | 지정된 비밀번호로 [Presentation](../presentation/)를 암호화합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(다른 NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(다른 NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | 프레젠테이션이 비밀번호로 보호된 경우에만 이 속성이 의미가 있습니다. true이면 프레젠테이션 파일에서 문서 속성이 암호화됩니다. false이면 프레젠테이션이 암호화된 동안 문서 속성이 공개됩니다. **bool**을 읽습니다. |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | 프레젠테이션 암호화에 사용되는 비밀번호를 가져옵니다. 읽기 전용 [System::String](../../system/string/). |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | 이 인스턴스가 암호화되었는지 여부를 나타내는 값을 가져옵니다. 읽기 전용 **bool**. |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | 프레젠테이션 파일이 비밀번호로 보호되고 해당 파일의 문서 속성이 공개된 경우에만 이 속성이 의미가 있습니다. true 값은 비밀번호 없이 암호화된 프레젠테이션 파일에서 문서 속성만 로드된다는 의미이며, false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드한다는 의미입니다. 프레젠테이션이 암호화되지 않은 경우 속성 값은 항상 false입니다. 암호화된 파일의 문서 속성이 공개되지 않은 경우에도 속성 값은 항상 false입니다. Presentation.EncryptDocumentProperties가 true인 경우 IsOnlyDocumentPropertiesLoaded 속성 값은 항상 false입니다. 읽기 전용 **bool**. |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | 이 프레젠테이션이 쓰기 보호되어 있는지 여부를 나타내는 값을 가져옵니다. 읽기 전용 **bool**. |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | 읽기 전용 권고를 가져옵니다. **bool**을 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [RemoveEncryption](./removeencryption/)() override | 암호화를 제거합니다. |
| void [RemoveWriteProtection](./removewriteprotection/)() override | 이 프레젠테이션의 쓰기 보호를 제거합니다. |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | 프레젠테이션이 비밀번호로 보호된 경우에만 이 속성이 의미가 있습니다. true이면 프레젠테이션 파일에서 문서 속성이 암호화됩니다. false이면 프레젠테이션이 암호화된 동안 문서 속성이 공개됩니다. **bool**을 씁니다. |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | 읽기 전용 권고를 설정합니다. **bool**을 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | 지정된 비밀번호로 이 프레젠테이션의 쓰기 보호를 설정합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현한 잠금 해제입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IProtectionManager](../iprotectionmanager/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)