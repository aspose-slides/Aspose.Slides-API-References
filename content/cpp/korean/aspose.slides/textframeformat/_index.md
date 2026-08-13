---
title: TextFrameFormat
second_title: Aspose.Slides for C++ API 참조
description: TextFrame의 formatTextFrameFormatting 속성을 포함합니다.
type: docs
weight: 5461
url: /ko/aspose.slides/textframeformat/
---
## TextFrameFormat 클래스

[TextFrame](../textframe/)의 formatTextFrameFormatting 속성을 포함합니다.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 객체와 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않으며 NaN도 포함됩니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이션합니다. IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않으며 NaN도 포함됩니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | 수직 앵커 텍스트를 [TextFrame](../textframe/)에서 반환합니다. 읽기 [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | 텍스트의 자동 맞춤 모드를 반환합니다. 읽기 [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | [NullableBool::True](../nullablebool/)이면 텍스트가 상자 내부에서 수평으로 가운데 정렬되어야 합니다. 읽기 [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | 텍스트 영역의 열 수를 반환합니다. 이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다. 값 0은 정의되지 않음을 의미합니다. 읽기 **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | 텍스트 영역의 텍스트 열 사이 간격을 반환합니다(포인트 단위). 열이 1개 이상일 때만 적용됩니다. 이 값은 양수여야 하며, 그렇지 않으면 0으로 설정됩니다. 읽기 **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | 3-D 회전 효과가 적용되었더라도 텍스트를 평면으로 유지하는지 가져옵니다. 읽기 **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | [TextFrame](../textframe/)에서 아래쪽 여백(포인트)을 반환합니다. 읽기 **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | [TextFrame](../textframe/)에서 왼쪽 여백(포인트)을 반환합니다. 읽기 **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | [TextFrame](../textframe/)에서 오른쪽 여백(포인트)을 반환합니다. 읽기 **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | [TextFrame](../textframe/)에서 위쪽 여백(포인트)을 반환합니다. 읽기 **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate 객체를 반환합니다. 읽기 전용 [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | 경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않으면 동반되는 도형의 회전이 사용됩니다. 지정된 경우 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 적용됩니다. 이 속성과 TextVerticalType 속성의 미리 정의된 수직 유형을 종합한 시각적 텍스트 회전 값을 반환합니다. 읽기 **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | 텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 지정 각도를 종합한 시각적 텍스트 회전 값을 반환합니다. 읽기 [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | [ThreeDFormat](../threedformat/) 객체를 반환합니다. 읽기 전용 [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | 텍스트 래핑 모양을 가져옵니다. 읽기 [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | 텍스트가 [TextFrame](../textframe/)의 여백에서 래핑되면 **True**. 읽기 [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | 상속이 적용된 효과적인 텍스트 프레임 서식 데이터를 가져옵니다. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType이 설명하는 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 유형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | [TextFrame](../textframe/)에서 수직 앵커 텍스트를 설정합니다. 쓰기 [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | 텍스트의 자동 맞춤 모드를 설정합니다. 쓰기 [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | [NullableBool::True](../nullablebool/)이면 텍스트가 상자 내부에서 수평으로 가운데 정렬되어야 합니다. 쓰기 [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | 텍스트 영역의 열 수를 설정합니다. 이 값은 양수여야 합니다. 그렇지 않으면 0으로 설정됩니다. 값 0은 정의되지 않음을 의미합니다. 쓰기 **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | 텍스트 영역의 텍스트 열 사이 간격을 설정합니다(포인트 단위). 열이 1개 이상일 때만 적용됩니다. 이 값은 양수여야 하며, 그렇지 않으면 0으로 설정됩니다. 쓰기 **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | 3-D 회전 효과가 적용되었더라도 텍스트를 평면으로 유지하도록 설정합니다. 쓰기 **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | [TextFrame](../textframe/)에서 아래쪽 여백(포인트)를 설정합니다. 쓰기 **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | [TextFrame](../textframe/)에서 왼쪽 여백(포인트)를 설정합니다. 쓰기 **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | [TextFrame](../textframe/)에서 오른쪽 여백(포인트)를 설정합니다. 쓰기 **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | [TextFrame](../textframe/)에서 위쪽 여백(포인트)를 설정합니다. 쓰기 **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | 경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않으면 동반되는 도형의 회전이 사용됩니다. 지정된 경우 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 적용됩니다. 이 속성과 TextVerticalType 속성의 미리 정의된 수직 유형을 종합한 시각적 텍스트 회전 값을 반환합니다. 쓰기 **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | 텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 지정 각도를 종합한 시각적 텍스트 회전 값을 반환합니다. 쓰기 [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | 텍스트 래핑 모양을 설정합니다. 쓰기 [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | 텍스트가 [TextFrame](../textframe/)의 여백에서 래핑되면 **True**. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용합니다. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용합니다. |
|  [TextFrameFormat](./textframeformat/)() | [TextFrameFormat](./) 클래스의 새 인스턴스를 초기화합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용합니다. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용합니다. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [PVIObject](../pviobject/)
* 클래스 [ITextFrameFormat](../itextframeformat/)
* 클래스 [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)