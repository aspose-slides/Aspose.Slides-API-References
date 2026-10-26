---
title: ILoadOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션을 로드할 때 추가 옵션(예: 형식 또는 기본 글꼴)을 지정할 수 있습니다.
type: docs
weight: 2796
url: /ko/aspose.slides/iloadoptions/
---
## ILoadOptions 클래스


프레젠테이션을 로드할 때 추가 옵션(예: 형식 또는 기본 글꼴)을 지정할 수 있습니다.

```cpp
class ILoadOptions : public virtual System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 동일하게 간주하는 C#-style 부동소수점 비교를 에뮬레이트합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않음). |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 동일하게 간주하는 C#-style 부동소수점 비교를 에뮬레이트합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않음). |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | 바이너리 대용량 객체(BLOB) 처리 동작을 관리하는 옵션을 나타냅니다(예: 임시 파일 사용 또는 메모리 내 최대 BLOB 바이트). 이러한 옵션은 특정 환경이나 요구 사항에 맞춰 최적의 성능/메모리 사용 비율을 설정하기 위해 설계되었습니다. |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | 원본 글꼴을 찾을 수 없는 경우 사용되는 아시아 글꼴을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | 원본 글꼴을 찾을 수 없는 경우 사용되는 일반 글꼴을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | 원본 글꼴을 찾을 수 없는 경우 사용되는 심볼 글꼴을 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | 프레젠테이션 텍스트의 기본 언어를 반환합니다. 읽기 [System::String](../../system/string/). |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | 프레젠테이션 로드 중에 [Aspose.Slides](../)가 모든 포함된 바이너리 객체를 삭제할지 여부를 결정합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | 프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. 이 글꼴은 프레젠테이션 전체 수명 동안 사용할 수 있으며 다른 프레젠테이션과 공유되지 않습니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | 중단 요청을 모니터링하기 위한 토큰입니다. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | 로드할 프레젠테이션의 형식을 반환합니다. 읽기 [Slides::LoadFormat](../loadformat/). |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | 이 속성은 프레젠테이션 파일이 암호로 보호된 경우에 의미가 있습니다. true이면 암호가 있는 프레젠테이션 파일에서 문서 속성만 로드되고 암호는 무시됩니다. false이면 올바른 암호를 사용하여 전체 암호화된 프레젠테이션을 로드합니다. 프레젠테이션이 암호화되지 않은 경우 이 속성 값은 항상 무시됩니다. 암호화된 파일의 문서 속성이 공개되지 않았고 값이 true이면 문서 속성을 로드할 수 없으며 예외가 발생합니다. 읽기 **bool**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | 비밀번호를 가져옵니다. 읽기 [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | 외부 리소스 로딩을 관리하는 콜백 인터페이스를 반환합니다. 읽기 [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | 추가 스프레드시트 동작을 지정하는 옵션을 나타냅니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | 경고를 수신하고 로드 프로세스를 계속할지 중단할지 결정하는 객체를 반환합니다. 읽기 [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 동일합니다. 사용자 정의 객체의 해시를 지원합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 동일합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 동일합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 동일합니다. 사용자 정의 타입 복제를 지원합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무것도 복사하지 않으며 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무것도 복사하지 않으며 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열과 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 문자열 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | 바이너리 대용량 객체(BLOB) 처리 동작을 관리하는 옵션을 나타냅니다(예: 임시 파일 사용 또는 메모리 내 최대 BLOB 바이트). 이러한 옵션은 특정 환경이나 요구 사항에 맞춰 최적의 성능/메모리 사용 비율을 설정하기 위해 설계되었습니다. |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | 원본 글꼴을 찾을 수 없는 경우 사용되는 아시아 글꼴을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | 원본 글꼴을 찾을 수 없는 경우 사용되는 일반 글꼴을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | 원본 글꼴을 찾을 수 없는 경우 사용되는 심볼 글꼴을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | 프레젠테이션 텍스트의 기본 언어를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | 프레젠테이션 로드 중에 [Aspose.Slides](../)가 모든 포함된 바이너리 객체를 삭제할지 여부를 결정합니다. |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | 프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. 이 글꼴은 프레젠테이션 전체 수명 동안 사용할 수 있으며 다른 프레젠테이션과 공유되지 않습니다. |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | 중단 요청을 모니터링하기 위한 토큰입니다. |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | 로드할 프레젠테이션의 형식을 설정합니다. 쓰기 [Slides::LoadFormat](../loadformat/). |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | 이 속성은 프레젠테이션 파일이 암호로 보호된 경우에 의미가 있습니다. true이면 암호가 있는 프레젠테이션 파일에서 문서 속성만 로드되고 암호는 무시됩니다. false이면 올바른 암호를 사용하여 전체 암호화된 프레젠테이션을 로드합니다. 프레젠테이션이 암호화되지 않은 경우 이 속성 값은 항상 무시됩니다. 암호화된 파일의 문서 속성이 공개되지 않았고 값이 true이면 문서 속성을 로드할 수 없으며 예외가 발생합니다. 쓰기 **bool**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | 비밀번호를 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | 외부 리소스 로딩을 관리하는 콜백 인터페이스를 설정합니다. 쓰기 [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | 추가 스프레드시트 동작을 지정하는 옵션을 나타냅니다. |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지 결정하는 객체를 설정합니다. 쓰기 [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 동일합니다. 사용자 정의 객체를 문자열로 변환하는 기능을 지원합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)