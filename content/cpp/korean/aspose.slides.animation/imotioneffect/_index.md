---
title: IMotionEffect
second_title: Aspose.Slides for C++ API 레퍼런스
description: 효과의 모션 효과 동작을 나타냅니다.
type: docs
weight: 287
url: /ko/aspose.slides.animation/imotioneffect/
---
## IMotionEffect 클래스

효과의 모션 효과 동작을 나타냅니다.

```cpp
class IMotionEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일에서 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일에서 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다(IEC 60559:1989에 따르면 NaN은 어떤 값(NaN 포함)과도 같지 않음). |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다(IEC 60559:1989에 따르면 NaN은 어떤 값(NaN 포함)과도 같지 않음). |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | 애니메이션 동작이 누적되는지 여부를 나타냅니다. 읽기 [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | 현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 여부를 나타냅니다. 읽기 [BehaviorAdditiveType](../behavioradditivetype/). |
| virtual **float** [get_Angle](./get_angle/)() | 모션 경로의 상대 각도를 설명합니다. **float**을(를) 읽으십시오. |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() | 애니메이션의 상대 오프셋 값을 설명합니다(퍼센트 단위). [System::Drawing::PointF](../../system.drawing/pointf/)을(를) 읽으십시오. |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() | 애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). [System::Drawing::PointF](../../system.drawing/pointf/)을(를) 읽으십시오. |
| virtual [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() | 모션 경로의 원점이 슬라이드 레이아웃이나 상위 요소와 같이 무엇을 기준으로 하는지 지정합니다. [MotionOriginType](../motionorigintype/)을(를) 읽으십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() | 애니메이션 모션을 위한 경로 기본형과 좌표를 지정합니다. [IMotionPath](../imotionpath/)을(를) 읽으십시오. |
| virtual [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() | 도형이 이동할 때 모션 경로가 어떻게 움직이는지 지정합니다. [MotionPathEditMode](../motionpatheditmode/)을(를) 읽으십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | 동작의 속성을 나타냅니다. 읽기 전용 [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() | X 각도로 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. [System::Drawing::PointF](../../system.drawing/pointf/)을(를) 읽으십시오. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | 효과 동작의 타이밍 속성을 나타냅니다. [ITiming](../itiming/)을(를) 읽으십시오. |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() | 애니메이션 모션 효과의 목표 위치를 지정합니다(퍼센트 단위). [System::Drawing::PointF](../../system.drawing/pointf/)을(를) 읽으십시오. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식의 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무 것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | 애니메이션 동작이 누적되는지 여부를 나타냅니다. [NullableBool](../../aspose.slides/nullablebool/)에 씁니다. |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | 현재 애니메이션 동작이 다른 실행 중인 애니메이션과 결합되는지 여부를 나타냅니다. [BehaviorAdditiveType](../behavioradditivetype/)에 씁니다. |
| virtual void [set_Angle](./set_angle/)(**float**) | 모션 경로의 상대 각도를 설명합니다. **float**에 씁니다. |
| virtual void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) | 애니메이션의 상대 오프셋 값을 설명합니다(퍼센트 단위). [System::Drawing::PointF](../../system.drawing/pointf/)에 씁니다. |
| virtual void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) | 애니메이션을 시작할 x/y 좌표를 지정합니다(퍼센트 단위). [System::Drawing::PointF](../../system.drawing/pointf/)에 씁니다. |
| virtual void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) | 모션 경로의 원점이 슬라이드 레이아웃이나 상위 요소와 같이 무엇을 기준으로 하는지 지정합니다. [MotionOriginType](../motionorigintype/)에 씁니다. |
| virtual void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) | 애니메이션 모션을 위한 경로 기본형과 좌표를 지정합니다. [IMotionPath](../imotionpath/)에 씁니다. |
| virtual void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) | 도형이 이동할 때 모션 경로가 어떻게 움직이는지 지정합니다. [MotionPathEditMode](../motionpatheditmode/)에 씁니다. |
| virtual void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) | X 각도로 모션 경로를 회전시키는 데 사용되는 회전 중심을 설명합니다. [System::Drawing::PointF](../../system.drawing/pointf/)에 씁니다. |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | 효과 동작의 타이밍 속성을 나타냅니다. [ITiming](../itiming/)에 씁니다. |
| virtual void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) | 애니메이션 모션 효과의 목표 위치를 지정합니다(퍼센트 단위). [System::Drawing::PointF](../../system.drawing/pointf/)에 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IBehavior](../ibehavior/)
* 네임스페이스 [Aspose::Slides::Animation](../)
* 라이브러리 [Aspose.Slides](../../)