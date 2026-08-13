---
title: IPptxOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: OpenXml 프레젠테이션(PPTX, PPSX, POTX, PPTM, PPSM, POTM)을 저장하기 위한 옵션을 나타냅니다.
type: docs
weight: 300
url: /ko/aspose.slides.export/ipptxoptions/
---
## IPptxOptions 클래스

OpenXml 프레젠테이션(PPTX, PPSX, POTX, PPTM, PPSM, POTM)을 저장하기 위한 옵션을 나타냅니다.

```cpp
class IPptxOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 시맨틱을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일의 부동 소수점 비교를 에뮬레이트합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 여기서는 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일의 부동 소수점 비교를 에뮬레이트합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 여기서는 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual [Aspose::Slides::Export::CompressionLevel](../compressionlevel/) [get_CompressionLevel](./get_compressionlevel/)() | 프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 [CompressionLevel::Level6](../compressionlevel/)입니다. |
| virtual [Aspose::Slides::Export::Conformance](../conformance/) [get_Conformance](./get_conformance/)() | [Presentation](../../aspose.slides/presentation/) 문서가 준수하는 호환성 클래스를 지정합니다. 기본값은 [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/)입니다. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환합니다. [System::String](../../system/string/)를 읽습니다. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 그라데이션의 시각적 스타일을 반환합니다. [GradientStyle](../../aspose.slides/gradientstyle/)를 읽습니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 진행률 업데이트를 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| virtual **bool** [get_RefreshThumbnail](./get_refreshthumbnail/)() | 프레젠테이션 썸네일이 새로 고쳐질지 여부를 지정합니다. **bool**을 읽습니다. 기본값은 **true**입니다. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**을 읽습니다. 기본값은 **false**입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 경고를 수신하고 로드 프로세스가 계속 진행될지 중단될지를 결정하는 객체를 반환합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)를 읽습니다. |
| virtual [Aspose::Slides::Export::Zip64Mode](../zip64mode/) [get_Zip64Mode](./get_zip64mode/)() | [Presentation](../../aspose.slides/presentation/) 문서에 ZIP64 형식을 사용할지 여부를 지정합니다. 기본값은 [Zip64Mode::IfNecessary](../zip64mode/)입니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형을 복제할 수 있게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_CompressionLevel](./set_compressionlevel/)([Aspose::Slides::Export::CompressionLevel](../compressionlevel/)) | 프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 [CompressionLevel::Level6](../compressionlevel/)입니다. |
| virtual void [set_Conformance](./set_conformance/)([Aspose::Slides::Export::Conformance](../conformance/)) | [Presentation](../../aspose.slides/presentation/) 문서가 준수하는 호환성 클래스를 지정합니다. 기본값은 [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/)입니다. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 설정합니다. [System::String](../../system/string/)를 씁니다. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 그라데이션의 시각적 스타일을 설정합니다. [GradientStyle](../../aspose.slides/gradientstyle/)를 씁니다. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 진행률 업데이트를 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| virtual void [set_RefreshThumbnail](./set_refreshthumbnail/)(**bool**) | 프레젠테이션 썸네일이 새로 고쳐질지 여부를 지정합니다. **bool**를 씁니다. 기본값은 **true**입니다. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**를 씁니다. 기본값은 **false**입니다. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 경고를 수신하고 로드 프로세스가 계속 진행될지 중단될지를 결정하는 객체를 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)를 씁니다. |
| virtual void [set_Zip64Mode](./set_zip64mode/)([Aspose::Slides::Export::Zip64Mode](../zip64mode/)) | [Presentation](../../aspose.slides/presentation/) 문서에 ZIP64 형식을 사용할지 여부를 지정합니다. 기본값은 [Zip64Mode::IfNecessary](../zip64mode/)입니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문장의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ISaveOptions](../isaveoptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)