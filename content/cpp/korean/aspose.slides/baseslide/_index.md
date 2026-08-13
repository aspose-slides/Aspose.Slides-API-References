---
title: BaseSlide
second_title: Aspose.Slides for C++ API 레퍼런스
description: 모든 슬라이드 유형에 대한 공통 데이터를 나타냅니다.
type: docs
weight: 170
url: /ko/aspose.slides/baseslide/
---
## BaseSlide 클래스

Represents common data for all slide types.

```cpp
class BaseSlide : public virtual Aspose::Slides::IBaseSlide,
                  public Aspose::Slides::IDOMObject,
                  public Aspose::Slides::IStyleColorOwner
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | 이 슬라이드에 대한 유효한 테마를 반환합니다. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | 두 [IBaseSlide](../ibaseslide/) 인스턴스가 같은지 여부를 결정합니다. 반환 값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다. 모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교에서는 고유 식별자 값(예: SlideId) 및 동적 콘텐츠(예: Date [Placeholder](../placeholder/)의 현재 날짜 값)는 고려되지 않습니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](./findshapebyalttext/)([System::String](../../system/string/)) override | 지정된 대체 텍스트를 가진 도형을 최초로 찾습니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](./get_background/)() override | 슬라이드 배경을 반환합니다. 읽기 전용 [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](./get_control/)(**int32_t**) override | 지정된 인덱스에 있는 ActiveX 컨트롤을 반환합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](./get_controls/)() override | 슬라이드의 ActiveX 컨트롤 컬렉션을 반환합니다. 읽기 전용 [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | 슬라이드의 사용자 지정 데이터를 반환합니다. 읽기 전용 [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | 포함된 하이퍼링크에 대한 쉬운 접근을 제공합니다. 읽기 전용 [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | 슬라이드의 이름을 반환합니다. 읽기 [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | [IPresentation](../ipresentation/) 인터페이스를 반환합니다. 읽기 전용 [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) override | 지정된 인덱스에 있는 도형을 반환합니다. 읽기 전용 [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() override | 슬라이드의 도형들을 반환합니다. 읽기 전용 [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](./get_showmastershapes/)() | 마스터 슬라이드의 도형이 슬라이드에 표시될지 여부를 지정합니다. 마스터 슬라이드 자체의 경우 이 속성은 항상 **false**를 반환합니다. 읽기 **bool**. |
| **uint32_t** [get_SlideId](./get_slideid/)() override | 슬라이드의 ID를 반환합니다. 읽기 전용 **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](./get_slideshowtransition/)() override | 지정된 슬라이드가 슬라이드 쇼 중에 진행되는 방식에 대한 정보를 포함하는 Transition 객체를 반환합니다. 읽기 전용 [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](./get_timeline/)() override | 애니메이션 타임라인 객체를 반환합니다. 읽기 전용 [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 버전입니다. 사용자 지정 객체의 해싱을 활성화합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 버전입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 버전입니다. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | 모든 허용 가능한 도형의 모든 단락에서 동일한 형식의 실행을 결합합니다. |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | 모든 허용 가능한 도형의 모든 단락에서 동일한 형식의 실행을 결합합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 버전입니다. 사용자 지정 타입의 복제 기능을 제공합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 유형 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | 슬라이드의 이름을 설정합니다. 쓰기 [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) | 마스터 슬라이드의 도형이 슬라이드에 표시될지 여부를 지정합니다. 마스터 슬라이드 자체의 경우 이 속성은 항상 **false**를 반환합니다. 쓰기 **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아니라)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용해야 합니다. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용해야 합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 버전입니다. 사용자 지정 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용해야 합니다. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용해야 합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [IBaseSlide](../ibaseslide/)
* 클래스 [IDOMObject](../idomobject/)
* 클래스 [IStyleColorOwner](../istylecolorowner/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)