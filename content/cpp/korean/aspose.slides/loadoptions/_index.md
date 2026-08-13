---
title: LoadOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션을 로드할 때 형식이나 기본 글꼴과 같은 추가 옵션을 지정할 수 있습니다.
type: docs
weight: 4395
url: /ko/aspose.slides/loadoptions/
---
## LoadOptions 클래스

Allows to specify additional options (such as format or default font) when loading a presentation.

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 모방합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 모방합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | 임시 파일 사용 또는 메모리 내 최대 BLOB 바이트와 같은 Binary Large Objects (BLOB) 처리 동작을 관리하는 데 사용할 수 있는 옵션을 나타냅니다. 이러한 옵션은 특정 환경이나 요구사항에 대해 최적의 성능/메모리 사용 비율을 설정하기 위해 설계되었습니다. |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | 소스 폰트를 찾을 수 없을 때 사용하는 Asian 글꼴을 반환합니다. [System::String](../../system/string/)을 읽으십시오. |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | 소스 폰트를 찾을 수 없을 때 사용하는 Regular 글꼴을 반환합니다. [System::String](../../system/string/)을 읽으십시오. |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | 소스 폰트를 찾을 수 없을 때 사용하는 Symbol 글꼴을 반환합니다. [System::String](../../system/string/)을 읽으십시오. |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | 프레젠테이션 텍스트의 기본 언어를 반환합니다. [System::String](../../system/string/)을 읽으십시오. |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | [Aspose.Slides](../)가 프레젠테이션 로드 중 모든 내장 바이너리 객체를 삭제할지 여부를 결정합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | 프레젠테이션에서 사용할 외부 폰트의 소스를 지정합니다. 이러한 폰트는 프레젠테이션 전체 수명 동안 사용 가능하며 다른 프레젠테이션과 공유되지 않습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | 중단 요청을 모니터링하기 위한 토큰입니다. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | 로드할 프레젠테이션의 형식을 반환합니다. [Slides::LoadFormat](../loadformat/)을 읽으십시오. |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | 프레젠테이션 파일이 비밀번호로 보호된 경우에만 의미가 있는 속성입니다. true 값은 암호화된 프레젠테이션 파일에서 문서 속성만 로드하고 비밀번호를 무시한다는 의미이며, false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드한다는 의미입니다. 프레젠테이션이 암호화되지 않은 경우 이 속성 값은 항상 무시됩니다. 암호화된 파일의 문서 속성이 공개되지 않았고 속성 값이 true인 경우 문서 속성을 로드할 수 없으며 예외가 발생합니다. **bool**을 읽으십시오. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | 비밀번호를 가져옵니다. [System::String](../../system/string/)을 읽으십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | 외부 리소스 로드를 관리하는 콜백 인터페이스를 반환합니다. [IResourceLoadingCallback](../iresourceloadingcallback/)을 읽으십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | 스프레드시트 옵션을 가져옵니다. 예를 들어, 이러한 옵션은 차트의 수식 계산에 영향을 미칩니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | 경고를 수신하고 로드 과정이 계속될지 중단될지를 결정하는 객체를 반환합니다. [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)을 읽으십시오. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시화를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| [LoadOptions](./loadoptions/)() | 새 기본 로드 옵션을 생성합니다. |
| [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | 새 로드 옵션을 생성합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조에 따라 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | 임시 파일 사용 또는 메모리 내 최대 BLOB 바이트와 같은 Binary Large Objects (BLOB) 처리 동작을 관리하는 데 사용할 수 있는 옵션을 나타냅니다. 이러한 옵션은 특정 환경이나 요구사항에 대해 최적의 성능/메모리 사용 비율을 설정하기 위해 설계되었습니다. |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | 소스 폰트를 찾을 수 없을 때 사용할 Asian 글꼴을 설정합니다. [System::String](../../system/string/)에 씁니다. |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | 소스 폰트를 찾을 수 없을 때 사용할 Regular 글꼴을 설정합니다. [System::String](../../system/string/)에 씁니다. |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | 소스 폰트를 찾을 수 없을 때 사용할 Symbol 글꼴을 설정합니다. [System::String](../../system/string/)에 씁니다. |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | 프레젠테이션 텍스트의 기본 언어를 설정합니다. [System::String](../../system/string/)에 씁니다. |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | [Aspose.Slides](../)가 프레젠테이션 로드 중 모든 내장 바이너리 객체를 삭제할지 여부를 결정합니다. |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | 프레젠테이션에서 사용할 외부 폰트의 소스를 지정합니다. 이러한 폰트는 프레젠테이션 전체 수명 동안 사용 가능하며 다른 프레젠테이션과 공유되지 않습니다. |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | 중단 요청을 모니터링하기 위한 토큰입니다. |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | 로드할 프레젠테이션의 형식을 설정합니다. [Slides::LoadFormat](../loadformat/)에 씁니다. |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | 프레젠테이션 파일이 비밀번호로 보호된 경우에만 의미가 있는 속성입니다. true 값은 암호화된 프레젠테이션 파일에서 문서 속성만 로드하고 비밀번호를 무시한다는 의미이며, false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드한다는 의미입니다. 프레젠테이션이 암호화되지 않은 경우 이 속성 값은 항상 무시됩니다. 암호화된 파일의 문서 속성이 공개되지 않았고 속성 값이 true인 경우 문서 속성을 로드할 수 없으며 예외가 발생합니다. **bool**에 씁니다. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | 비밀번호를 설정합니다. [System::String](../../system/string/)에 씁니다. |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | 외부 리소스 로드를 관리하는 콜백 인터페이스를 설정합니다. [IResourceLoadingCallback](../iresourceloadingcallback/)에 씁니다. |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | 스프레드시트 옵션을 가져옵니다. 예를 들어, 이러한 옵션은 차트의 수식 계산에 영향을 미칩니다. |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 경고를 수신하고 로드 과정이 계속될지 중단될지를 결정하는 객체를 설정합니다. [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)에 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 관련 항목

* Class [ILoadOptions](../iloadoptions/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)