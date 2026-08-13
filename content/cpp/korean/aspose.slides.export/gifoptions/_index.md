---
title: GifOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: GIF 내보내기 옵션을 나타냅니다.
type: docs
weight: 53
url: /ko/aspose.slides.export/gifoptions/
---
## GifOptions 클래스

GIF 내보내기 옵션을 나타냅니다.

```cpp
class GifOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IGifOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 동등하게 간주되는 C#-style 부동 소수점 비교를 에뮬레이션합니다. IEC 60559:1989에 따르면 NaN은 NaN을 포함한 어떤 값과도 동등하지 않지만, 이 메서드는 그렇게 동작합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 동등하게 간주되는 C#-style 부동 소수점 비교를 에뮬레이션합니다. IEC 60559:1989에 따르면 NaN은 NaN을 포함한 어떤 값과도 동등하지 않지만, 이 메서드는 그렇게 동작합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **int32_t** [get_DefaultDelay](./get_defaultdelay/)() override | 기본 지연 시간 [ms]을 가져옵니다. [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/) 메서드가 호출되지 않은 경우 이 값이 사용됩니다. 기본값은 1000입니다. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 원본 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 반환합니다. [System::String](../../system/string/)을 읽습니다. |
| **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() override | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. 기본값은 false입니다. |
| [System::Drawing::Size](../../system.drawing/size/) [get_FrameSize](./get_framesize/)() override | 프레임 크기를 가져옵니다. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 그라디언트의 시각적 스타일을 반환합니다. [GradientStyle](../../aspose.slides/gradientstyle/)을 읽습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 진행률을 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**을 읽습니다. 기본값은 **false**입니다. |
| **int32_t** [get_TransitionFps](./get_transitionfps/)() override | 전환 FPS [frames/sec]를 가져옵니다. 기본값은 25입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 경고를 수신하고 로드 프로세스가 계속될지 중단될지 결정하는 객체를 반환하거나 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)을 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| [GifOptions](./gifoptions/)() | [GifOptions](./) 클래스를 새 인스턴스로 초기화합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultDelay](./set_defaultdelay/)(**int32_t**) override | 기본 지연 시간 [ms]을 설정합니다. [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/) 메서드가 호출되지 않은 경우 이 값이 사용됩니다. 기본값은 1000입니다. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 원본 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 설정합니다. [System::String](../../system/string/)에 기록합니다. |
| void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) override | 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. 기본값은 false입니다. |
| void [set_FrameSize](./set_framesize/)([System::Drawing::Size](../../system.drawing/size/)) override | 프레임 크기를 설정합니다. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 그라디언트의 시각적 스타일을 설정합니다. [GradientStyle](../../aspose.slides/gradientstyle/)에 기록합니다. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 진행률을 백분율로 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)를 참조하십시오. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 프레젠테이션을 저장할 때 JavaScript 호출이 포함된 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**에 기록합니다. 기본값은 **false**입니다. |
| void [set_TransitionFps](./set_transitionfps/)(**int32_t**) override | 전환 FPS [frames/sec]를 설정합니다. 기본값은 25입니다. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 경고를 수신하고 로드 프로세스가 계속될지 중단될지 결정하는 객체를 반환하거나 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)에 기록합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 포인터 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시자를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

다음 예제는 사용자 정의 설정을 사용하여 프레젠테이션을 애니메이션 GIF로 변환하는 방법을 보여줍니다. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto gifOptions = System::MakeObject<GifOptions>();

gifOptions->set_FrameSize(System::Drawing::Size(960, 720)); // 결과 GIF의 크기
gifOptions->set_DefaultDelay(2000); // 각 슬라이드가 다음 슬라이드로 전환될 때까지 표시되는 시간
gifOptions->set_TransitionFps(35); // 전환 애니메이션 품질을 향상시키기 위해 FPS를 높입니다

pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 참조

* 클래스 [SaveOptions](../saveoptions/)
* 클래스 [IGifOptions](../igifoptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)