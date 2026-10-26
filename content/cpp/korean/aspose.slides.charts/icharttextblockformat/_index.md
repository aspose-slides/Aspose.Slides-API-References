---
title: IChartTextBlockFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트 텍스트 요소에 대한 서식 속성을 나타냅니다.
type: docs
weight: 885
url: /ko/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat 클래스

Represents formatting properties for chart text elements.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style 부동 소수점 비교를 에뮬레이션합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만 동일하게 간주됩니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style 부동 소수점 비교를 에뮬레이션합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만 동일하게 간주됩니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | [TextFrame](../../aspose.slides/textframe/)에서 수직 앵커 텍스트를 반환합니다. 읽기 [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | 텍스트의 자동 맞춤 모드를 반환합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과가 없음). 읽기 [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | [NullableBool::True](../../aspose.slides/nullablebool/)이면 텍스트가 박스 안에서 가로로 가운데 정렬되어야 합니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | [TextFrame](../../aspose.slides/textframe/)에서 아래쪽 여백(포인트)을 반환합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 효과 없음). 읽기 **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | [TextFrame](../../aspose.slides/textframe/)에서 왼쪽 여백(포인트)을 반환합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 효과 없음). 읽기 **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | [TextFrame](../../aspose.slides/textframe/)에서 오른쪽 여백(포인트)을 반환합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 효과 없음). 읽기 **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | [TextFrame](../../aspose.slides/textframe/)에서 위쪽 여백(포인트)을 반환합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 효과 없음). 읽기 **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | 경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. 지정되지 않은 경우, 동반되는 도형의 회전이 사용됩니다. 지정된 경우, 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 적용됩니다. 이 속성과 TextVerticalType 속성의 사전 정의 수직 유형으로 요약된 시각적 텍스트 회전 값을 반환합니다. 읽기 **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 정의 각도로 요약된 시각적 텍스트 회전 값을 반환합니다. 읽기 [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | [TextFrame](../../aspose.slides/textframe/)의 여백에서 텍스트가 줄바꿈되는 경우 **True**. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2007/2013 전체 지원). 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무 것도 복사하지 않으며, 새로운 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | [TextFrame](../../aspose.slides/textframe/)에서 수직 앵커 텍스트를 설정합니다. 쓰기 [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | 텍스트의 자동 맞춤 모드를 설정합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 렌더링에 효과 없음). 쓰기 [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | [NullableBool::True](../../aspose.slides/nullablebool/)이면 텍스트가 박스 안에서 가로로 가운데 정렬되어야 합니다. 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | [TextFrame](../../aspose.slides/textframe/)에서 아래쪽 여백(포인트)을 설정합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 효과 없음). 쓰기 **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | [TextFrame](../../aspose.slides/textframe/)에서 왼쪽 여백(포인트)을 설정합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 효과 없음). 쓰기 **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | [TextFrame](../../aspose.slides/textframe/)에서 오른쪽 여백(포인트)을 설정합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 효과 없음). 쓰기 **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | [TextFrame](../../aspose.slides/textframe/)에서 위쪽 여백(포인트)을 설정합니다. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2013에서 전체 지원; PowerPoint 2007에서는 효과 없음). 쓰기 **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | 경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. 지정되지 않은 경우 동반 도형의 회전이 사용됩니다. 지정된 경우 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 적용됩니다. 이 속성과 TextVerticalType 속성의 사전 정의 수직 유형으로 요약된 시각적 텍스트 회전 값을 반환합니다. 쓰기 **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | 텍스트 방향을 결정합니다. 이 속성과 RotationAngle 속성의 사용자 정의 각도로 요약된 시각적 텍스트 회전 값을 반환합니다. 쓰기 [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | [TextFrame](../../aspose.slides/textframe/)의 여백에서 텍스트가 줄바꿈되는 경우 **True**. 이 속성을 변경하면 [DataLabel](../datalabel/) 및 [DataLabelFormat](../datalabelformat/) 차트 부분에만 특정 영향을 줄 수 있습니다(PowerPoint 2007/2013 전체 지원). 쓰기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)