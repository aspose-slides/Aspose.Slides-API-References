---
title: IGroupShapeLock
second_title: Aspose.Slides for C++ API 레퍼런스
description: 부모 GroupShape에서 비활성화된 작업을 결정합니다.
type: docs
weight: 2497
url: /ko/aspose.slides/igroupshapelock/
---
## IGroupShapeLock 클래스

부모 [GroupShape](../groupshape/)에서 비활성화된 작업을 결정합니다.

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 IEC 60559:1989에 따라 NaN은 어떤 값과도 같지 않음에도 불구하고 C# 스타일 부동 소수점 비교에서 동일하게 간주하도록 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 IEC 60559:1989에 따라 NaN은 어떤 값과도 같지 않음에도 불구하고 C# 스타일 부동 소수점 비교에서 동일하게 간주하도록 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | 리사이즈할 때 도형이 가로 세로 비율을 유지해야 하는지 여부를 판단합니다. 읽기 **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | 이 도형을 그룹에 추가하는 것이 금지되는지 여부를 판단합니다. 읽기 **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | 모든 잠금 플래그가 비활성화된 경우 true를 반환합니다. 읽기 전용 **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | 이 도형을 이동하는 것이 금지되는지 여부를 판단합니다. 읽기 **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | 이 도형의 회전 각도를 변경하는 것이 금지되는지 여부를 판단합니다. 읽기 **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | 이 도형을 선택하는 것이 금지되는지 여부를 판단합니다. 읽기 **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | 이 도형의 크기 조정을 금지하는지 여부를 판단합니다. 읽기 **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | 이 그룹 도형을 분할하는 것이 금지되는지 여부를 판단합니다. 읽기 **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 구현입니다. 사용자 정의 객체의 해시화를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 구현입니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 구현입니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 구현입니다. 사용자 정의 유형 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | 리사이즈 시 도형이 가로 세로 비율을 유지해야 하는지 여부를 판단합니다. 쓰기 **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | 이 도형을 그룹에 추가하는 것이 금지되는지 여부를 판단합니다. 쓰기 **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | 이 도형을 이동하는 것이 금지되는지 여부를 판단합니다. 쓰기 **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | 이 도형의 회전 각도를 변경하는 것이 금지되는지 여부를 판단합니다. 쓰기 **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | 이 도형을 선택하는 것이 금지되는지 여부를 판단합니다. 쓰기 **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | 이 도형의 크기 조정을 금지하는지 여부를 판단합니다. 쓰기 **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | 이 그룹 도형을 분할하는 것이 금지되는지 여부를 판단합니다. 쓰기 **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 구현입니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IBaseShapeLock](../ibaseshapelock/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)