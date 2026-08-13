---
title: ISwfOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션을 SWF 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
weight: 469
url: /ko/aspose.slides.export/iswfoptions/
---
## ISwfOptions 클래스

Provides options that control how a presentation is saved in SWF format.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(그리고 NaN 자체와도) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(그리고 NaN 자체와도) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| virtual **bool** [get_Compressed](./get_compressed/)() | 생성된 SWF 문서를 압축할지 여부를 지정합니다. 기본값은 **true**입니다. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 원본 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환합니다. [System::String](../../system/string/)을 읽습니다. |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | 콘텍스트 메뉴를 활성화/비활성화합니다. 기본값은 true입니다. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 그라디언트의 시각적 스타일을 반환합니다. [GradientStyle](../../aspose.slides/gradientstyle/)을 읽습니다. |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | JPEG 이미지의 품질을 지정합니다.  

 기본값은 95입니다. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | 뷰어 오른쪽 상단 모서리에 로고로 표시될 이미지입니다.  

 이미지는 32x64 픽셀 PNG 이미지여야 하며, 그렇지 않으면 로고가 올바르게 표시되지 않을 수 있습니다. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | 로고에 대한 전체 하이퍼링크 주소를 가져옵니다. [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/)가 지정된 경우에만 적용됩니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 진행률 업데이트를 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | 하단 패널을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | 전체 화면 버튼을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 **false**입니다. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | 왼쪽 패널을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | 페이지 주위의 경계를 표시할지 여부를 지정합니다. 기본값은 true입니다. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | 페이지 스테퍼를 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | 검색 섹션을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | 전체 상단 패널을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 프레젠테이션 저장 시 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**을 읽습니다. 기본값은 **false**입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | 프레젠테이션 [ISlidesLayoutOptions](../islideslayoutoptions/)을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다. 이 속성은 **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** 유형의 객체 할당을 지원하지 않습니다. |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | 왼쪽 패널을 연 상태로 시작합니다. flashvars에서 재정의할 수 있습니다. 기본값은 false입니다. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | 생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. 기본값은 **true**입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 경고를 수신하고 로드 프로세스를 계속할지 중단할지 결정하는 객체를 반환합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)을 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 겁니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | 생성된 SWF 문서를 압축할지 여부를 지정합니다. 기본값은 **true**입니다. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 원본 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 설정합니다. [System::String](../../system/string/)에 씁니다. |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | 콘텍스트 메뉴를 활성화/비활성화합니다. 기본값은 true입니다. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 그라디언트의 시각적 스타일을 설정합니다. [GradientStyle](../../aspose.slides/gradientstyle/)에 씁니다. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | JPEG 이미지의 품질을 지정합니다.  

 기본값은 95입니다. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 뷰어 오른쪽 상단 모서리에 로고로 표시될 이미지입니다.  

 이미지는 32x64 픽셀 PNG 이미지여야 하며, 그렇지 않으면 로고가 올바르게 표시되지 않을 수 있습니다. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | 로고에 대한 전체 하이퍼링크 주소를 설정합니다. [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/)가 지정된 경우에만 적용됩니다. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 진행률 업데이트를 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | 하단 패널을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | 전체 화면 버튼을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 생성된 문서에 숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은 **false**입니다. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | 왼쪽 패널을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | 페이지 주위의 경계를 표시할지 여부를 지정합니다. 기본값은 true입니다. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | 페이지 스테퍼를 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | 검색 섹션을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | 전체 상단 패널을 표시/숨깁니다. flashvars에서 재정의할 수 있습니다. 기본값은 true입니다. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 프레젠테이션 저장 시 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**에 씁니다. 기본값은 **false**입니다. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | 프레젠테이션 [ISlidesLayoutOptions](../islideslayoutoptions/)을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 설정합니다. 이 속성은 **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** 유형의 객체 할당을 지원하지 않습니다. |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | 왼쪽 패널을 연 상태로 시작합니다. flashvars에서 재정의할 수 있습니다. 기본값은 false입니다. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | 생성된 SWF 문서에 통합 문서 뷰어를 포함할지 여부를 지정합니다. 기본값은 **true**입니다. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 경고를 수신하고 로드 프로세스를 계속할지 중단할지 결정하는 객체를 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)에 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 포인터 대신)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환하는 것을 가능하게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [ISaveOptions](../isaveoptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)