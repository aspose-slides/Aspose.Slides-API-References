---
title: Pen
second_title: Aspose.Slides for C++ API 레퍼런스
description: "그려지는 선과 곡선의 색상, 너비 등과 같은 속성을 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택에 직접 생성하거나 new 연산자를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인자로 전달하여 사용하십시오."
type: docs
weight: 183
url: /ko/system.drawing/pen/
---
## Pen 클래스

Represents properties such as color, width etc. of the lines and curves being drawn. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Pen : public System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Pen](./)\> [Clone](./clone/)() | 현재 객체의 복사본을 반환합니다. |
| void [Dispose](./dispose/)() | 현재 객체가 획득한 모든 운영 리소스를 해제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 구현합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음). |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 구현합니다(IEC 60559:1989에 따르면 NaN은 어떤 값과도, NaN 자체와도 같지 않음). |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| [Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/) [get_Alignment](./get_alignment/)() const | 현재 [Pen](./) 객체의 정렬을 나타내는 값을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\> [get_Brush](./get_brush/)() | 이 펜의 [Brush](../brush/) 객체를 반환합니다. |
| [Color](../color/) [get_Color](./get_color/)() const | 이 펜의 색상을 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CompoundArray](./get_compoundarray/)() const | 복합 펜을 지정하는 값 배열을 반환합니다. |
| [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/) [get_DashCap](./get_dashcap/)() const | 대시 라인의 양쪽 끝에 사용되는 캡을 나타내는 값을 반환합니다. |
| **float** [get_DashOffset](./get_dashoffset/)() const | 선 시작점에서 대시 패턴 시작점까지의 거리를 반환합니다. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_DashPattern](./get_dashpattern/)() const | 대시 라인에서 사용자 정의 대시 패턴을 나타내는 배열을 반환합니다. |
| [Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/) [get_DashStyle](./get_dashstyle/)() const | 현재 [Pen](./) 객체의 대시 스타일을 나타내는 값을 반환합니다. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_EndCap](./get_endcap/)() const | 현재 [Pen](./) 객체의 끝 라인 캡을 나타내는 값을 반환합니다. |
| [Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/) [get_LineJoin](./get_linejoin/)() const | 이 [Pen](./) 객체가 그린 선들의 연결 방식을 나타내는 값을 반환합니다. |
| **float** [get_MiterLimit](./get_miterlimit/)() const | 각진 코너에서 조인 두께의 한계를 반환합니다. |
| [Drawing2D::PenType](../../system.drawing.drawing2d/pentype/) [get_PenType](./get_pentype/)() const | 구현되지 않음. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_StartCap](./get_startcap/)() const | 현재 [Pen](./) 객체의 시작 라인 캡을 나타내는 값을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | 현재 객체가 나타내는 펜의 기하학적 변환을 지정하는 Matrix 객체의 복사본을 반환합니다. |
| **float** [get_Width](./get_width/)() const | 현재 [Pen](./) 객체의 너비를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 지원합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 지원합니다. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 현재 객체의 변환 행렬에 지정된 행렬을 곱합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
|  [Pen](./pen/)(const [Color](../color/)\&) | 지정된 색상을 나타내는 새 [Pen](./) 객체를 구성합니다. |
|  [Pen](./pen/)(const [Color](../color/)\&, **float**) | 지정된 색상과 너비를 나타내는 새 [Pen](./) 객체를 구성합니다. |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | 새 [Pen](./) 객체를 구성하고 지정된 [Brush](../brush/) 객체로 초기화합니다. |
|  [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**) | 새 [Pen](./) 객체를 구성하고 지정된 [Brush](../brush/) 객체로 초기화합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체와 nullptr를 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [ResetTransform](./resettransform/)() | 현재 객체의 변환 행렬을 초기화하여 단위 행렬이 되도록 합니다. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 지정된 순서와 각도로 로컬 기하 변환을 회전시킵니다. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 지정된 순서와 인수로 로컬 기하 변환을 스케일링합니다. |
| void [set_Alignment](./set_alignment/)([Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/)) | 현재 [Pen](./) 객체의 정렬을 설정합니다. |
| void [set_Brush](./set_brush/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | 이 펜의 [Brush](../brush/) 객체를 설정합니다. |
| void [set_Color](./set_color/)(const [Color](../color/)\&) | 이 펜의 색상을 설정합니다. |
| void [set_CompoundArray](./set_compoundarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | 복합 펜을 지정하는 값 배열을 설정합니다. |
| void [set_CustomEndCap](./set_customendcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | 사용자 정의 끝 라인 캡을 설정합니다. |
| void [set_CustomStartCap](./set_customstartcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | 사용자 정의 시작 라인 캡을 설정합니다. |
| void [set_DashCap](./set_dashcap/)([Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | 대시 라인의 양쪽 끝에 사용되는 캡을 지정하는 값을 설정합니다. |
| void [set_DashOffset](./set_dashoffset/)(**float**) | 선 시작점에서 대시 패턴 시작점까지의 거리를 설정합니다. |
| void [set_DashPattern](./set_dashpattern/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | 대시 라인에서 사용자 정의 대시 패턴을 지정하는 배열을 설정합니다. 배열은 교대로 나타나는 대시와 공백의 길이를 지정하는 숫자들로 구성됩니다. |
| void [set_DashStyle](./set_dashstyle/)([Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/)) | 현재 [Pen](./) 객체의 대시 스타일을 지정하는 값을 설정합니다. |
| void [set_EndCap](./set_endcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | 현재 [Pen](./) 객체의 끝 라인 캡을 설정합니다. |
| void [set_LineJoin](./set_linejoin/)([Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/)) | 이 [Pen](./) 객체가 그린 선들의 연결 방식을 지정하는 값을 설정합니다. |
| void [set_MiterLimit](./set_miterlimit/)(**float**) | 각진 코너에서 조인 두께의 한계를 설정합니다. |
| void [set_StartCap](./set_startcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | 현재 [Pen](./) 객체의 시작 라인 캡을 설정합니다. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | 현재 객체가 나타내는 펜의 기하학적 변환을 지정하는 Matrix 객체를 설정합니다. |
| void [set_Width](./set_width/)(**float**) | 현재 [Pen](./) 객체의 너비를 설정합니다. |
| void [SetLineCap](./setlinecap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | 구현되지 않음. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아니라)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 지정된 순서와 차원으로 로컬 기하 변환을 평행 이동합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)