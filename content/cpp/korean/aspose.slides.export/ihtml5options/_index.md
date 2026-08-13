---
title: IHtml5Options
second_title: Aspose.Slides for C++ API 참조
description: HTML5 내보내기 옵션을 나타냅니다.
type: docs
weight: 170
url: /ko/aspose.slides.export/ihtml5options/
---
## IHtml5Options 클래스

HTML5 내보내기 옵션을 나타냅니다.

```cpp
class IHtml5Options : public virtual Aspose::Slides::Export::ISaveOptions
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일의 부동 소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만 두 NaN은 동일한 것으로 간주됩니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일의 부동 소수점 비교를 에뮬레이트합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만 두 NaN은 동일한 것으로 간주됩니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **bool** [get_AnimateShapes](./get_animateshapes/)() | 도형 애니메이션 옵션을 반환합니다. 읽기 **bool**. |
| virtual **bool** [get_AnimateTransitions](./get_animatetransitions/)() | 전환 애니메이션 옵션을 반환합니다. 읽기 **bool**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 소스 폰트를 찾을 수 없는 경우에 사용되는 폰트를 반환합니다. [System::String](../../system/string/)을(를) 읽습니다. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | 리그처를 사용하지 않고 텍스트가 렌더링되는지 여부를 나타내는 값을 가져옵니다. **true**로 설정하면 렌더링된 출력에서 리그처가 비활성화됩니다. 기본값은 **false**입니다. |
| virtual **bool** [get_EmbedImages](./get_embedimages/)() | 이미지 삽입 옵션을 반환합니다. 읽기 **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 그라디언트의 시각적 스타일을 반환합니다. [GradientStyle](../../aspose.slides/gradientstyle/)을(를) 읽습니다. |
| virtual [System::String](../../system/string/) [get_OutputPath](./get_outputpath/)() | 외부 리소스가 저장될 위치를 결정합니다. [System::String](../../system/string/)을(를) 읽습니다. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | 그림 압축 레벨을 나타냅니다. [PicturesCompression](../picturescompression/)을(를) 읽습니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 백분율로 진행 상황 업데이트를 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)을(를) 참조하십시오. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. 읽기 **bool**. 기본값은 **false**입니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다 [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 경고를 받고 로딩 프로세스가 계속될지 중단될지를 결정하는 객체를 반환합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)을(를) 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사체입니다. 사용자 정의 객체의 해싱을 활성화합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사체입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자의 유사체입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사체입니다. 사용자 정의 형식 복제를 활성화합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_AnimateShapes](./set_animateshapes/)(**bool**) | 도형 애니메이션 옵션을 설정합니다. **bool**을 씁니다. |
| virtual void [set_AnimateTransitions](./set_animatetransitions/)(**bool**) | 전환 애니메이션 옵션을 설정합니다. **bool**을 씁니다. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 소스 폰트를 찾을 수 없는 경우에 사용되는 폰트를 설정합니다. [System::String](../../system/string/)을 씁니다. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | 리그처를 사용하지 않고 텍스트를 렌더링할지 여부를 나타내는 값을 설정합니다. **true**로 설정하면 렌더링된 출력에서 리그처가 비활성화됩니다. 기본값은 **false**입니다. |
| virtual void [set_EmbedImages](./set_embedimages/)(**bool**) | 이미지 삽입 옵션을 설정합니다. **bool**을 씁니다. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 그라디언트의 시각적 스타일을 설정합니다. [GradientStyle](../../aspose.slides/gradientstyle/)을(를) 씁니다. |
| virtual void [set_OutputPath](./set_outputpath/)([System::String](../../system/string/)) | 외부 리소스가 저장될 위치를 결정합니다. [System::String](../../system/string/)을(를) 씁니다. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | 그림 압축 레벨을 나타냅니다. [PicturesCompression](../picturescompression/)을(를) 씁니다. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 백분율로 진행 상황 업데이트를 저장하기 위한 콜백 객체를 나타냅니다. [IProgressCallback](../../aspose.slides/iprogresscallback/)을(를) 참조하십시오. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 프레젠테이션을 저장할 때 JavaScript 호출이 있는 하이퍼링크를 건너뛸지 여부를 지정합니다. **bool**을 씁니다. 기본값은 **false**입니다. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 설정합니다 [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 경고를 받고 로딩 프로세스가 계속될지 중단될지를 결정하는 객체를 설정합니다. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)을(를) 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운터를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사체입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운터를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 비고

예제:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-shapes-and-transitions.html", SaveFormat::Html5, options);
```

## 참고

* 클래스 [ISaveOptions](../isaveoptions/)
* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)