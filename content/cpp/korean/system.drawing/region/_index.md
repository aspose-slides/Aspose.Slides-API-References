---
title: Region
second_title: Aspose.Slides for C++ API 참조
description: "그래픽 도형의 내부를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 유형의 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 래핑하고 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 261
url: /ko/system.drawing/region/
---
## Region 클래스

그래픽 도형의 내부를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 유형의 인스턴스를 만들지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 래핑하고 해당 포인터를 함수 인수로 전달하십시오.

```cpp
class Region : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | 현재 객체의 복사본을 반환합니다. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역 중 이 영역과 교차하지 않는 부분으로 교체합니다. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역 중 이 영역과 교차하지 않는 부분으로 교체합니다. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 현재 객체가 나타내는 영역을 지정된 경로로 정의된 영역 중 이 영역과 교차하지 않는 부분으로 교체합니다. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 현재 객체가 나타내는 영역을 지정된 영역 중 이 영역과 교차하지 않는 부분으로 교체합니다. |
| void [Dispose](./dispose/)() | 현재 객체가 획득한 모든 운영 체제 리소스를 해제합니다. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 지정된 그리기 표면에서 지정된 영역이 현재 객체가 나타내는 영역과 동일한지 여부를 판단합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역을 제외한 결과로 교체합니다. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역을 제외한 결과로 교체합니다. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 현재 객체가 나타내는 영역을 지정된 경로로 정의된 영역을 제외한 결과로 교체합니다. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 현재 객체가 나타내는 영역을 지정된 영역을 제외한 결과로 교체합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | [Graphics](../graphics/) 객체의 그리기 표면에서 이 [Region](./)를 둘러싼 사각형을 나타내는 [RectangleF](../rectanglef/) 구조체를 가져옵니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | 현재 객체가 나타내는 영역을 정의하는 데이터를 포함하는 RegionData 객체를 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | 지정된 행렬 변환이 적용된 후 이 [Region](./)을 근사화하는 [RectangleF](../rectanglef/) 구조체 배열을 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역과의 교집합 결과로 교체합니다. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역과의 교집합 결과로 교체합니다. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 현재 객체가 나타내는 영역을 지정된 경로로 정의된 영역과의 교집합 결과로 교체합니다. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 현재 객체가 나타내는 영역을 지정된 영역과의 교집합 결과로 교체합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 지정된 그리기 표면에서 현재 객체가 나타내는 영역이 내부가 비어 있는지 여부를 판단합니다. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 지정된 그리기 표면에서 현재 객체가 나타내는 영역이 내부가 무한한지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | 지정된 점이 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | 지정된 점이 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | 지정된 사각형의 일부가 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | 지정된 사각형의 일부가 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 지정된 그래픽을 사용하여 지정된 점이 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 지정된 그래픽을 사용하여 지정된 점이 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 지정된 그래픽을 사용하여 지정된 사각형의 일부가 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | 지정된 그래픽을 사용하여 지정된 사각형의 일부가 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | 지정된 점이 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | 지정된 그래픽을 사용하여 지정된 점이 현재 객체가 나타내는 영역 내에 포함되는지 여부를 판단합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| void [MakeEmpty](./makeempty/)() | 현재 객체를 내부가 비어 있도록 초기화합니다. |
| void [MakeInfinite](./makeinfinite/)() | 이 영역 객체를 내부가 무한하도록 초기화합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입을 복제할 수 있게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조 기준으로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
|  [Region](./region/)() | [Region](./) 클래스로 새로운 인스턴스를 구성합니다. |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | 지정된 사각형으로 정의된 영역을 나타내는 [Region](./) 클래스의 새로운 인스턴스를 구성합니다. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | 지정된 사각형으로 정의된 영역을 나타내는 [Region](./) 클래스의 새로운 인스턴스를 구성합니다. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 지정된 경로로 정의된 영역을 나타내는 [Region](./) 클래스의 새로운 인스턴스를 구성합니다. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | 지정된 RegionData 객체로 정의된 영역을 나타내는 [Region](./) 클래스의 새로운 인스턴스를 구성합니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | 지정된 행렬을 사용하여 이 영역을 변환합니다. |
| void [Transform](./transform/)(const SkMatrix\&) | 지정된 행렬을 사용하여 이 영역을 변환합니다. |
| void [Translate](./translate/)(int, int) | 지정된 양만큼 영역의 좌표를 이동합니다. |
| void [Translate](./translate/)(**float**, **float**) | 지정된 양만큼 영역의 좌표를 이동합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역과의 합집합 연산 결과로 교체합니다. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역과의 합집합 결과로 교체합니다. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 현재 객체가 나타내는 영역을 지정된 경로로 정의된 영역과의 합집합 결과로 교체합니다. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 현재 객체가 나타내는 영역을 지정된 영역과의 합집합 결과로 교체합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역과 교차하지 않는 부분으로 교체합니다. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역과 교차하지 않는 부분으로 교체합니다. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 현재 객체가 나타내는 영역을 지정된 경로로 정의된 영역과 교차하지 않는 부분으로 교체합니다. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | 현재 객체가 나타내는 영역을 지정된 영역과 교차하지 않는 부분으로 교체합니다. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
| virtual  [~Region](./~region/)() | 소멸자. |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)