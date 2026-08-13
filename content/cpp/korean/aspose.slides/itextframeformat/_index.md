---
title: ITextFrameFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: TextFrame의 서식 속성을 포함합니다.
type: docs
weight: 4083
url: /ko/aspose.slides/itextframeformat/
---
## ITextFrameFormat 클래스

[TextFrame](../textframe/)의 서식 속성을 포함합니다.

```cpp
class ITextFrameFormat : public virtual System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 시맨틱을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따라 어느 값과도 같지 않음에도 불구하고 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따라 어느 값과도 같지 않음에도 불구하고 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | [TextFrame](../textframe/)에서 수직 앵커 텍스트를 반환합니다. 읽기 [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | 텍스트의 자동 맞춤 모드를 반환합니다. 읽기 [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | [NullableBool::True](../nullablebool/)인 경우 텍스트를 상자 안에서 수평으로 가운데 정렬해야 합니다. 읽기 [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | 텍스트 영역의 열 수를 반환합니다. 이 값은 양수여야 하며, 그렇지 않으면 0으로 설정됩니다. 값 0은 정의되지 않음을 의미합니다. 읽기 **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | 텍스트 영역의 텍스트 열 사이 간격을 포인트 단위로 반환합니다(열이 2개 이상일 때만 적용). 이 값은 양수여야 하며, 그렇지 않으면 0으로 설정됩니다. 읽기 **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | 3D 장면에서 텍스트를 완전히 제외하도록 반환하거나 설정합니다. 읽기 **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | [TextFrame](../textframe/)에서 하단 여백(포인트)을 반환합니다. 읽기 **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | [TextFrame](../textframe/)에서 좌측 여백(포인트)을 반환합니다. 읽기 **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | [TextFrame](../textframe/)에서 우측 여백(포인트)을 반환합니다. 읽기 **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | [TextFrame](../textframe/)에서 상단 여백(포인트)을 반환합니다. 읽기 **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | 경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. 지정되지 않은 경우 동반 도형의 회전이 사용됩니다. 지정된 경우 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용되는 동시에 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 속성 TextVerticalType에 정의된 수직 유형을 종합한 시각적 텍스트 회전값을 반환합니다. 읽기 **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | 텍스트 스타일을 반환합니다. 읽기 전용 [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 텍스트 방향을 결정합니다. 이 속성과 속성 RotationAngle에 정의된 사용자 지정 각도를 종합한 시각적 텍스트 회전값을 반환합니다. 읽기 [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | 텍스트에 대한 3D 효과 속성을 나타내는 [ThreeDFormat](../threedformat/) 객체를 반환합니다. 읽기 전용 [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | 텍스트 래핑 모양을 가져옵니다. 읽기 [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | 텍스트가 [TextFrame](../textframe/)의 여백에서 래핑되는 경우 **True**. 읽기 [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | 상속이 적용된 효과적인 텍스트 프레임 서식 데이터를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | [TextFrame](../textframe/)에서 수직 앵커 텍스트를 설정합니다. 쓰기 [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | 텍스트의 자동 맞춤 모드를 설정합니다. 쓰기 [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | [NullableBool::True](../nullablebool/)인 경우 텍스트를 상자 안에서 수평으로 가운데 정렬하도록 설정합니다. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | 텍스트 영역의 열 수를 설정합니다. 이 값은 양수여야 하며, 그렇지 않으면 0으로 설정됩니다. 값 0은 정의되지 않음을 의미합니다. 쓰기 **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | 텍스트 영역의 텍스트 열 사이 간격을 포인트 단위로 설정합니다(열이 2개 이상일 때만 적용). 이 값은 양수여야 하며, 그렇지 않으면 0으로 설정됩니다. 쓰기 **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | 3D 장면에서 텍스트를 완전히 제외하도록 설정하거나 반환합니다. 쓰기 **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | [TextFrame](../textframe/)에서 하단 여백(포인트)을 설정합니다. 쓰기 **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | [TextFrame](../textframe/)에서 좌측 여백(포인트)을 설정합니다. 쓰기 **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | [TextFrame](../textframe/)에서 우측 여백(포인트)을 설정합니다. 쓰기 **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | [TextFrame](../textframe/)에서 상단 여백(포인트)을 설정합니다. 쓰기 **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | 경계 상자 내 텍스트에 적용되는 사용자 정의 회전을 지정합니다. 지정되지 않은 경우 동반 도형의 회전이 사용됩니다. 지정된 경우 도형과 독립적으로 적용됩니다. 즉, 도형에 회전이 적용되는 동시에 텍스트 자체에도 회전이 적용될 수 있습니다. 이 속성과 속성 TextVerticalType에 정의된 수직 유형을 종합한 시각적 텍스트 회전값을 설정합니다. 쓰기 **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | 텍스트 방향을 설정합니다. 이 속성과 속성 RotationAngle에 정의된 사용자 지정 각도를 종합한 시각적 텍스트 회전값을 설정합니다. 쓰기 [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | 텍스트 래핑 모양을 설정합니다. 쓰기 [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | [TextFrame](../textframe/)의 여백에서 텍스트가 래핑되는 경우 **True**. 쓰기 [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유 대신)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)