---
title: ISVGOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: SVG 옵션을 나타냅니다.
type: docs
weight: 404
url: /ko/aspose.slides.export/isvgoptions/
---
## ISVGOptions 클래스

SVG 옵션을 나타냅니다.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않으며, NaN도 포함됩니다). |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않으며, NaN도 포함됩니다). |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 소스 글꼴을 찾을 수 없을 경우 사용되는 글꼴을 반환합니다. [System::String](../../system/string/)을(를) 읽습니다. |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | 잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화됩니다(파일이 커질 수 있습니다). 읽기 **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. 읽기 **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | 텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져옵니다. **true**로 설정하면 렌더링 결과에서 합자가 비활성화됩니다. 기본값은 **false**입니다. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | FromCornerX 및 FromCenter 그라데이션 분할을 비활성화합니다. 읽기 **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1은 마커에 대한 inset을 정의할 수 없습니다. [Aspose.Slides](../../aspose.slides/) SVG 작성 엔진은 이 문제에 대한 해결책으로 화살표가 있는 선 끝을 잘라서 선이 마커와 겹치지 않도록 합니다. 이 옵션은 해당 동작을 끕니다. 읽기 **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | 외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. 읽기 [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 그라데이션의 시각적 스타일을 반환합니다. 읽기 [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | 내보낸 문서에서 [Ink](../../aspose.slides.ink/) 객체의 외관을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | JPEG 인코딩 품질을 결정합니다. 읽기 **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | 메타파일 래스터화에 대한 최소 해상도 제한을 반환합니다. 읽기 **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | 그림 압축 수준을 나타냅니다. 읽기 [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 백분율로 진행 상황을 저장하는 콜백 객체를 나타냅니다. 참조 [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | 사용자가 도형 변환을 제어할 수 있는 콜백 인터페이스를 반환하고 설정합니다. 읽기 [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기 **bool**. 기본값은 **false**입니다. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | 렌더링 시 도형에 지정된 회전을 수행할지 여부를 결정합니다. 읽기 **bool**. 기본값은 true입니다. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | 텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. 읽기 **bool**. 기본값은 false입니다. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | 슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다. 읽기 **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 경고를 받으며 로드 프로세스를 계속할지 중단할지 결정하는 객체를 반환합니다. 읽기 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입의 클론을 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 소스 글꼴을 찾을 수 없을 경우 사용할 글꼴을 설정합니다. [System::String](../../system/string/)을 씁니다. |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | 잘린 부분이 문서의 일부로 남아 있는지 여부를 나타내는 부울 플래그입니다. true이면 잘린 부분이 제거되고, false이면 문서에 직렬화됩니다(파일이 커질 수 있습니다). 쓰기 **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | SVG에서 3D 텍스트가 비활성화되는지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | 텍스트가 합자를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 설정합니다. **true**로 설정하면 렌더링 결과에서 합자가 비활성화됩니다. 기본값은 **false**입니다. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | FromCornerX 및 FromCenter 그라데이션 분할을 비활성화합니다. 쓰기 **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1은 마커에 대한 inset을 정의할 수 없습니다. [Aspose.Slides](../../aspose.slides/) SVG 작성 엔진은 이 문제에 대한 해결책으로 화살표가 있는 선 끝을 잘라서 선이 마커와 겹치지 않도록 합니다. 이 옵션은 해당 동작을 끕니다. 쓰기 **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | 외부에서 로드된 글꼴을 처리하는 방식을 결정합니다. 쓰기 [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 그라데이션의 시각적 스타일을 설정합니다. 쓰기 [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | JPEG 인코딩 품질을 결정합니다. 쓰기 **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | 메타파일 래스터화에 대한 최소 해상도 제한을 설정합니다. 쓰기 **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | 그림 압축 수준을 나타냅니다. 쓰기 [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 백분율로 진행 상황 저장을 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | 사용자가 도형 변환을 제어할 수 있는 콜백 인터페이스를 반환하고 설정합니다. 쓰기 [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 프레젠테이션 저장 시 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. 쓰기 **bool**. 기본값은 **false**입니다. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | 렌더링 시 도형에 지정된 회전을 수행할지 여부를 결정합니다. 쓰기 **bool**. 기본값은 true입니다. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | 텍스트 프레임을 렌더링 영역에 포함시킬지 여부를 결정합니다. 쓰기 **bool**. 기본값은 false입니다. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | 슬라이드의 텍스트를 그래픽으로 저장할지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 경고를 받고 로드 프로세스를 계속할지 중단할지 결정하는 객체를 설정합니다. 쓰기 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 weak 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 weak 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제(언락)를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ISaveOptions](../isaveoptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)