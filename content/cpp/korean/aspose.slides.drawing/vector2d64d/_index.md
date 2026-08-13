---
title: Vector2d64d
second_title: Aspose.Slides C++ API 레퍼런스
description: double 구성 요소를 가진 2D 벡터
type: docs
weight: 66
url: /ko/aspose.slides.drawing/vector2d64d/
---
## Vector2d64d 클래스

2D vector with **double** components

```cpp
class Vector2d64d : public System::Object,
                    public System::Details::BoxableObjectBase
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **double** [Dot](./dot/)([Vector2d64d](./)) | 두 벡터의 스칼라 곱을 계산합니다. |
| **bool** [Equals](./equals/)(const [Vector2d64d](./)\&) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 동일하게 간주되는 C# 스타일 부동소수점 비교를 구현합니다. IEC 60559:1989에 따르면 NaN은 NaN을 포함한 어떤 값과도 같지 않지만, 여기서는 두 NaN을 동일하게 취급합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 동일하게 간주되는 C# 스타일 부동소수점 비교를 구현합니다. IEC 60559:1989에 따르면 NaN은 NaN을 포함한 어떤 값과도 같지 않지만, 여기서는 두 NaN을 동일하게 취급합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **double** [get_Length](./get_length/)() | 벡터의 스칼라 길이를 가져옵니다. 읽기 전용 **double**. |
| [Vector2d64d](./) [get_Norm](./get_norm/)() | 정규 벡터를 가져옵니다. 읽기 전용 [Vector2d64d](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| **bool** [IsNull](./isnull/)() const |  |
| void [Lock](../../system/object/lock/)() | C# lock() 구문의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| static [Vector2d64d](./) [Max](./max/)([Vector2d64d](./), [Vector2d64d](./)) |  |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입의 복제를 가능하게 합니다. |
| static [Vector2d64d](./) [Min](./min/)([Vector2d64d](./), [Vector2d64d](./)) |  |
| [Vector2d64d](./) [Normalize](./normalize/)() | 길이가 1인 공선 벡터를 생성합니다. 이 벡터는 길이가 0이어서는 안 됩니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하세요. |
| void [SwapXY](./swapxy/)() | X와 Y를 교환합니다. |
| [System::String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| [Vector2d32f](../vector2d32f/) [ToVector2d32f](./tovector2d32f/)() | [Vector2d32f](../vector2d32f/) 로 변환합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하세요. |
| [Vector2d64d](./vector2d64d/)(**double**, **double**) | 생성자 |
| [Vector2d64d](./vector2d64d/)([System::Drawing::PointF](../../system.drawing/pointf/)) | 생성자 |
| [Vector2d64d](./vector2d64d/)() |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [One](./one/) |  |
| static [Zero](./zero/) |  |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)