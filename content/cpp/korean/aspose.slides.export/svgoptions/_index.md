---
title: SVGOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: SVG 옵션을 나타냅니다.
type: docs
weight: 703
url: /ko/aspose.slides.export/svgoptions/
---
## SVGOptions 클래스

SVG 옵션을 나타냅니다.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | 기본 설정을 반환합니다. 읽기 전용 [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 원본 글꼴을 찾을 수 없을 경우 사용되는 글꼴을 반환합니다. 읽기 [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | 불리언 플래그는 잘라낸 부분이 문서에 남아 있는지 여부를 나타냅니다. true이면 잘라낸 부분이 제거되고, false이면 문서에 직렬화됩니다(파일 크기가 커질 수 있음). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | SVG에서 3D 텍스트가 비활성화되는지 결정합니다. 읽기 **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | 텍스트가 합자(ligature)를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져옵니다. **true**로 설정하면 렌더링 결과에서 합자가 비활성화됩니다. 기본값은 **false**입니다. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. 읽기 **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1은 마커에 대한 inset을 정의할 기능이 없습니다. [Aspose.Slides](../../aspose.slides/) SVG 쓰기 엔진은 이 문제를 해결하기 위해 화살표가 있는 선 끝을 잘라서 선이 마커와 겹치지 않게 합니다. 이 옵션은 해당 동작을 비활성화합니다. 읽기 **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | 외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. 읽기 [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 그라디언트의 시각적 스타일을 반환합니다. 읽기 [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | 내보낸 문서에서 [Ink](../../aspose.slides.ink/) 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | JPEG 인코딩 품질을 결정합니다. 읽기 **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | 메타파일 래스터화에 대한 최소 해상도 제한을 반환합니다. 읽기 **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | 그림 압축 수준을 나타냅니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 진행률을 백분율로 저장하는 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | 사용자가 도형 변환을 제어할 수 있는 콜백 인터페이스를 반환하고 설정합니다. 읽기 [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | 가장 간단하고 작은 SVG 파일 생성을 위한 설정을 반환합니다. 읽기 전용 [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 프레젠테이션 저장 시 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기 **bool**. 기본값은 **false**입니다. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | 렌더링 시 도형에 지정된 회전을 수행할지 여부를 결정합니다. 읽기 **bool**. 기본값은 true입니다. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | 텍스트 프레임이 렌더링 영역에 포함될지 여부를 결정합니다. 읽기 **bool**. 기본값은 false입니다. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | 슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다. 읽기 **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 경고를 수신하고 로드 프로세스의 지속 여부를 결정하는 객체를 반환하거나 설정합니다. 읽기 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | 가장 정확한 SVG 파일 생성을 위한 설정을 반환합니다. 읽기 전용 [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구현을 위한 잠금 기능을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 원본 글꼴을 찾을 수 없을 경우 사용되는 글꼴을 설정합니다. [System::String](../../system/string/)를 기록합니다. |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | 불리언 플래그는 잘라낸 부분이 문서에 남아 있는지 여부를 나타냅니다. true이면 잘라낸 부분이 제거되고, false이면 문서에 직렬화됩니다(파일 크기가 커질 수 있음). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | SVG에서 3D 텍스트가 비활성화되는지 결정합니다. **bool**를 기록합니다. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | 텍스트가 합자 없이 렌더링되는지 여부를 나타내는 값을 설정합니다. **true**로 설정하면 렌더링 결과에서 합자가 비활성화됩니다. 기본값은 **false**입니다. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | FromCornerX 및 FromCenter 그라디언트 분할을 비활성화합니다. **bool**를 기록합니다. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1은 마커에 대한 inset을 정의할 기능이 없습니다. [Aspose.Slides](../../aspose.slides/) SVG 쓰기 엔진은 이 문제를 해결하기 위해 화살표가 있는 선 끝을 잘라서 선이 마커와 겹치지 않게 합니다. 이 옵션은 해당 동작을 비활성화합니다. **bool**를 기록합니다. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | 외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. [SvgExternalFontsHandling](../svgexternalfontshandling/)를 기록합니다. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 그라디언트의 시각적 스타일을 설정합니다. [GradientStyle](../../aspose.slides/gradientstyle/)를 기록합니다. |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | JPEG 인코딩 품질을 결정합니다. **int32_t**를 기록합니다. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | 메타파일 래스터화에 대한 최소 해상도 제한을 설정합니다. **int32_t**를 기록합니다. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | 그림 압축 수준을 나타냅니다. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 진행률을 백분율로 저장하는 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | 사용자가 도형 변환을 제어할 수 있는 콜백 인터페이스를 반환하고 설정합니다. [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)를 기록하십시오. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 프레젠테이션 저장 시 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**를 기록합니다. 기본값은 **false**입니다. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | 렌더링 시 도형에 지정된 회전을 수행할지 여부를 결정합니다. **bool**를 기록합니다. 기본값은 true입니다. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | 텍스트 프레임이 렌더링 영역에 포함될지 여부를 결정합니다. **bool**를 기록합니다. 기본값은 false입니다. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | 슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다. **bool**를 기록합니다. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 경고를 수신하고 로드 프로세스의 지속 여부를 결정하는 객체를 반환하거나 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)를 기록합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 템플릿 인수 n번째를 약한 포인터(공유 대신)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
|  [SVGOptions](./svgoptions/)() | [SVGOptions](./) 클래스의 새 인스턴스를 초기화합니다. |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | [SVGOptions](./) 클래스의 새 인스턴스를 초기화하며, 링크 임베딩 컨트롤러 객체를 지정합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [SaveOptions](../saveoptions/)
* 클래스 [ISVGOptions](../isvgoptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)