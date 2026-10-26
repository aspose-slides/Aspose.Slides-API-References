---
title: GraphicsPath
second_title: Aspose.Slides for C++ API 레퍼런스
description: "연결된 선과 곡선의 집합을 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 66
url: /ko/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath 클래스


연결된 선과 곡선의 집합을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용하여 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오.

```cpp
class GraphicsPath : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | 현재 객체가 나타내는 경로에 지정된 타원호를 추가합니다. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | 현재 객체가 나타내는 경로에 지정된 타원호를 추가합니다. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | 현재 객체가 나타내는 경로에 지정된 타원호를 추가합니다. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | 현재 객체가 나타내는 경로에 지정된 타원호를 추가합니다. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | 현재 객체가 나타내는 경로에 지정된 3차 베지어 곡선을 추가합니다. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | 현재 객체가 나타내는 경로에 지정된 3차 베지어 곡선을 추가합니다. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | 현재 객체가 나타내는 경로에 지정된 3차 베지어 곡선을 추가합니다. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | 현재 객체가 나타내는 경로에 지정된 3차 베지어 곡선을 추가합니다. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 현재 도형에 연결된 3차 베지어 곡선들의 연속을 추가합니다. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 현재 도형에 연결된 3차 베지어 곡선들의 연속을 추가합니다. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | 현재 객체가 나타내는 경로에 지정된 닫힌 곡선을 추가합니다. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | 현재 객체가 나타내는 경로에 지정된 닫힌 곡선을 추가합니다. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | 현재 객체가 나타내는 경로에 지정된 곡선을 추가합니다. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | 현재 객체가 나타내는 경로에 지정된 곡선을 추가합니다. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | 현재 객체가 나타내는 경로에 지정된 곡선을 추가합니다. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | 현재 객체가 나타내는 경로에 지정된 곡선을 추가합니다. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | 현재 객체가 나타내는 경로에 지정된 타원을 추가합니다. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | 현재 객체가 나타내는 경로에 지정된 타원을 추가합니다. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | 현재 객체가 나타내는 경로에 지정된 타원을 추가합니다. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | 현재 객체가 나타내는 경로에 지정된 타원을 추가합니다. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | 현재 객체가 나타내는 경로에 지정된 선을 추가합니다. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | 현재 객체가 나타내는 경로에 지정된 선을 추가합니다. |
| void [AddLine](./addline/)(int, int, int, int) | 현재 객체가 나타내는 경로에 지정된 선을 추가합니다. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | 현재 객체가 나타내는 경로에 지정된 선을 추가합니다. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 현재 객체가 나타내는 경로에 연결된 선분들의 연속을 추가합니다. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 현재 객체가 나타내는 경로에 연결된 선분들의 연속을 추가합니다. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | 현재 객체가 나타내는 경로에 지정된 경로를 추가합니다. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | 현재 객체가 나타내는 경로에 파이 형태의 지정된 외곽선을 추가합니다. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | 현재 객체가 나타내는 경로에 파이 형태의 지정된 외곽선을 추가합니다. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | 현재 객체가 나타내는 경로에 파이 형태의 지정된 외곽선을 추가합니다. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | 현재 객체가 나타내는 경로에 지정된 다각형을 추가합니다. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | 현재 객체가 나타내는 경로에 지정된 다각형을 추가합니다. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | 현재 객체가 나타내는 경로에 지정된 사각형을 추가합니다. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | 현재 객체가 나타내는 경로에 지정된 사각형을 추가합니다. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | 현재 객체가 나타내는 경로에 사각형들의 연속을 추가합니다. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | 현재 객체가 나타내는 경로에 사각형들의 연속을 추가합니다. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 현재 객체가 나타내는 경로에 문자열 텍스트를 추가합니다. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 현재 객체가 나타내는 경로에 문자열 텍스트를 추가합니다. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 현재 객체가 나타내는 경로에 문자열 텍스트를 추가합니다. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | 현재 객체가 나타내는 경로에 문자열 텍스트를 추가합니다. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | 현재 객체의 복사본을 생성합니다. |
| void [CloseAllFigures](./closeallfigures/)() | 열려 있는 모든 도형을 닫고 새로운 도형을 시작합니다. |
| void [CloseFigure](./closefigure/)() | 현재 도형을 닫고 새로운 도형을 시작합니다. |
| void [Dispose](./dispose/)() | 현재 객체가 획득한 모든 운영 체제 리소스를 해제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(심지어 NaN과도) 같지 않지만, 두 NaN을 동등하게 고려하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(심지어 NaN과도) 같지 않지만, 두 NaN을 동등하게 고려하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| void [Flatten](./flatten/)() | 각 곡선을 평탄화하여 연결된 선들의 시리즈로 변환합니다. 평탄도 값 0.25가 사용됩니다. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | 각 곡선을 평탄화하여 연결된 선들의 시리즈로 변환합니다. 평탄도 값 0.25가 사용됩니다. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | 각 곡선을 평탄화하여 연결된 선들의 시리즈로 변환합니다. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | 현재 객체의 채우기 모드를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | 현재 객체가 나타내는 경로를 구성하는 점과 그 유형을 포함하는 [PathData](../pathdata/) 객체를 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | 현재 객체가 나타내는 경로를 구성하는 점들을 포함하는 배열을 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | 현재 객체가 나타내는 경로를 구성하는 점들의 타입을 나타내는 값을 포함하는 배열을 반환합니다. |
| int [get_PointCount](./get_pointcount/)() const | 현재 객체가 나타내는 경로의 점 수를 반환합니다. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | 지정된 행렬로 변환될 때 현재 객체가 나타내는 경로를 둘러싼 사각형을 나타내는 [RectangleF](../../system.drawing/rectanglef/) 객체를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | 현재 객체가 나타내는 경로에 포함된 도형 유형을 나타내는 Detail::FigureType 값들의 비트wise 결합 값을 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드의 유사 기능입니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | 경로의 마지막 점을 나타내는 [PointF](../../system.drawing/pointf/) 객체를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출의 유사 기능입니다. |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | 지정된 채우기 모드로 [GraphicsPath](./) 클래스를 새 인스턴스로 생성합니다. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | 지정된 경로를 나타내는 [GraphicsPath](./) 객체를 새 인스턴스로 생성합니다. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | 지정된 경로를 나타내는 [GraphicsPath](./) 객체를 새 인스턴스로 생성합니다. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자의 유사 기능입니다. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | 지정된 [Pen](../../system.drawing/pen/)로 그릴 때 이 [GraphicsPath](./)의 외곽선(아래)에 지정된 점이 포함되는지 여부를 나타냅니다. 구현되지 않음. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | 지정된 점이 현재 객체가 나타내는 경로 내부에 포함되는지 판단합니다. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | 지정된 점이 현재 객체가 나타내는 경로 내부에 포함되는지 판단합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드의 유사 기능입니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [Reset](./reset/)() | 모든 점을 제거하여 경로를 비웁니다. |
| void [Reverse](./reverse/)() | 이 [GraphicsPath](./)의 PathPoints 배열에서 점 순서를 역전시킵니다. |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | 현재 객체의 채우기 모드를 설정합니다. |
| void [SetMarkers](./setmarkers/)() | 구현되지 않음. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유 포인터 대신)로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운터를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [StartFigure](./startfigure/)() | 새 도형을 시작합니다. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드의 유사 기능입니다. 사용자 정의 객체를 문자열로 변환합니다. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | 지정된 변환 행렬을 적용하여 현재 객체가 나타내는 경로를 변환합니다. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운터를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운터를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | 이 경로를 원래 경로 주변의 외곽선으로 교체합니다. |
|  [~GraphicsPath](./~graphicspath/)() | 소멸자. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Drawing::Drawing2D](../)
* 라이브러리 [Aspose.Slides](../../)