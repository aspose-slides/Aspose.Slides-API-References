---
title: IAutoShapeLock
second_title: Aspose.Slides for C++ API 레퍼런스
description: 부모 AutoshapeEx에서 비활성화된 작업을 결정합니다.
type: docs
weight: 1379
url: /ko/aspose.slides/iautoshapelock/
---
## IAutoShapeLock 클래스

Determines which operations are disabled on the parent AutoshapeEx.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-style 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C#-style 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | 조정 값 변경이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | 화살표 머리 변경이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | 크기 조정 시 도형이 종횡비를 유지해야 하는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | 이 도형의 윤곽 직접 변경이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | 이 도형을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | 모든 잠금 플래그가 비활성화된 경우 true를 반환합니다. 읽기 전용 **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | 이 도형 이동이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | 이 도형의 회전 각도 변경이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | 이 도형 선택이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | 도형 유형 변경이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | 이 도형 크기 조정이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | 텍스트 편집이 금지되는지 여부를 결정합니다. **bool**을 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 단순히 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무 것도 복사하지 않으며, 단순히 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | 조정 값 변경이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | 화살표 머리 변경이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | 크기 조정 시 도형이 종횡비를 유지해야 하는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | 이 도형의 윤곽 직접 변경이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | 이 도형을 그룹에 추가하는 것이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | 이 도형 이동이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | 이 도형의 회전 각도 변경이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | 이 도형 선택이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | 도형 유형 변경이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | 이 도형 크기 조정이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | 텍스트 편집이 금지되는지 여부를 결정합니다. **bool**을 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [IBaseShapeLock](../ibaseshapelock/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)