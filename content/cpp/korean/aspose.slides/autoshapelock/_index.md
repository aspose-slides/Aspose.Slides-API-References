---
title: AutoShapeLock
second_title: Aspose.Slides for C++ API 레퍼런스
description: 부모 AutoshapeEx에서 비활성화된 작업이 어떤 것인지 결정합니다.
type: docs
weight: 79
url: /ko/aspose.slides/autoshapelock/
---
## AutoShapeLock 클래스

부모 AutoshapeEx에서 비활성화된 작업을 결정합니다.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN도 같지 않지만, 두 NaN을 같은 것으로 간주하는 C#-style 부동 소수점 비교를 에뮬레이션합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도, 포함 NaN도 같지 않지만, 두 NaN을 같은 것으로 간주하는 C#-style 부동 소수점 비교를 에뮬레이션합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | 조정 값 변경이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | 화살촉 변경이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | 크기 조정 시 형상이 가로세로 비율을 유지해야 하는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | 이 형상의 윤곽을 직접 변경하는 것이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | 이 형상을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | 모든 잠금 플래그가 비활성화된 경우 true를 반환합니다. 읽기 전용 **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | 이 형상의 이동이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | 이 형상의 회전 각도 변경이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | 이 형상의 선택이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | 형식 변경이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | 이 형상의 크기 조정이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | 텍스트 편집이 금지되는지 여부를 결정합니다. 읽기 **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스를 복사 생성하도록 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스를 복사 생성하도록 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 따라 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | 조정 값 변경이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | 화살촉 변경이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | 크기 조정 시 형상이 가로세로 비율을 유지해야 하는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | 이 형상의 윤곽을 직접 변경하는 것이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | 이 형상을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | 이 형상의 이동이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | 이 형상의 회전 각도 변경이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | 이 형상의 선택이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | 형식 변경이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | 이 형상의 크기 조정이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | 텍스트 편집이 금지되는지 여부를 결정합니다. 쓰기 **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [BaseShapeLock](../baseshapelock/)
* 클래스 [IAutoShapeLock](../iautoshapelock/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)