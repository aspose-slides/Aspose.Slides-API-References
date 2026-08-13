---
title: ColorMatrix
second_title: Aspose.Slides for C++ API 참조
description: "RGBAW 색 공간의 좌표를 포함하는 5x5 행렬을 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수에 인수로 전달하십시오."
type: docs
weight: 27
url: /ko/system.drawing.imaging/colormatrix/
---
## 메서드

RGBAW 색 공간의 좌표를 포함하는 5x5 행렬을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용하지 마십시오. 이렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오.

```cpp
class ColorMatrix : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | [ColorMatrix](./) 클래스의 새 인스턴스를 생성하고 단위 행렬의 값으로 초기화합니다. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | [ColorMatrix](./) 클래스의 새 인스턴스를 생성하고 지정된 값으로 초기화합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 객체를 C# [Object.Equals](../../system/object/equals/) 의미에 따라 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| **float** [get_Matrix00](./get_matrix00/)() const | 0번째 행 0번째 열의 값을 반환합니다. |
| **float** [get_Matrix01](./get_matrix01/)() const | 0번째 행 1번째 열의 값을 반환합니다. |
| **float** [get_Matrix02](./get_matrix02/)() const | 0번째 행 2번째 열의 값을 반환합니다. |
| **float** [get_Matrix03](./get_matrix03/)() const | 0번째 행 3번째 열의 값을 반환합니다. |
| **float** [get_Matrix04](./get_matrix04/)() const | 0번째 행 4번째 열의 값을 반환합니다. |
| **float** [get_Matrix10](./get_matrix10/)() const | 1번째 행 0번째 열의 값을 반환합니다. |
| **float** [get_Matrix11](./get_matrix11/)() const | 1번째 행 1번째 열의 값을 반환합니다. |
| **float** [get_Matrix12](./get_matrix12/)() const | 1번째 행 2번째 열의 값을 반환합니다. |
| **float** [get_Matrix13](./get_matrix13/)() const | 1번째 행 3번째 열의 값을 반환합니다. |
| **float** [get_Matrix14](./get_matrix14/)() const | 1번째 행 4번째 열의 값을 반환합니다. |
| **float** [get_Matrix20](./get_matrix20/)() const | 2번째 행 0번째 열의 값을 반환합니다. |
| **float** [get_Matrix21](./get_matrix21/)() const | 2번째 행 1번째 열의 값을 반환합니다. |
| **float** [get_Matrix22](./get_matrix22/)() const | 2번째 행 2번째 열의 값을 반환합니다. |
| **float** [get_Matrix23](./get_matrix23/)() const | 2번째 행 3번째 열의 값을 반환합니다. |
| **float** [get_Matrix24](./get_matrix24/)() const | 2번째 행 4번째 열의 값을 반환합니다. |
| **float** [get_Matrix30](./get_matrix30/)() const | 3번째 행 0번째 열의 값을 반환합니다. |
| **float** [get_Matrix31](./get_matrix31/)() const | 3번째 행 1번째 열의 값을 반환합니다. |
| **float** [get_Matrix32](./get_matrix32/)() const | 3번째 행 2번째 열의 값을 반환합니다. |
| **float** [get_Matrix33](./get_matrix33/)() const | 3번째 행 3번째 열의 값을 반환합니다. |
| **float** [get_Matrix34](./get_matrix34/)() const | 3번째 행 4번째 열의 값을 반환합니다. |
| **float** [get_Matrix40](./get_matrix40/)() const | 4번째 행 0번째 열의 값을 반환합니다. |
| **float** [get_Matrix41](./get_matrix41/)() const | 4번째 행 1번째 열의 값을 반환합니다. |
| **float** [get_Matrix42](./get_matrix42/)() const | 4번째 행 2번째 열의 값을 반환합니다. |
| **float** [get_Matrix43](./get_matrix43/)() const | 4번째 행 3번째 열의 값을 반환합니다. |
| **float** [get_Matrix44](./get_matrix44/)() const | 4번째 행 4번째 열의 값을 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해시를 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| **float** [idx_get](./idx_get/)(int, int) | 지정된 행과 열의 값을 반환합니다. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | 행렬의 지정된 위치에 값을 설정합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구현을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 할당 연산자. 실제로 아무것도 복사하지 않으며, 새 객체를 초기화하고 하위 클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_Matrix00](./set_matrix00/)(**float**) | 0번째 행 0번째 열에 값을 설정합니다. |
| void [set_Matrix01](./set_matrix01/)(**float**) | 0번째 행 1번째 열에 값을 설정합니다. |
| void [set_Matrix02](./set_matrix02/)(**float**) | 0번째 행 2번째 열에 값을 설정합니다. |
| void [set_Matrix03](./set_matrix03/)(**float**) | 0번째 행 3번째 열에 값을 설정합니다. |
| void [set_Matrix04](./set_matrix04/)(**float**) | 0번째 행 4번째 열에 값을 설정합니다. |
| void [set_Matrix10](./set_matrix10/)(**float**) | 1번째 행 0번째 열에 값을 설정합니다. |
| void [set_Matrix11](./set_matrix11/)(**float**) | 1번째 행 1번째 열에 값을 설정합니다. |
| void [set_Matrix12](./set_matrix12/)(**float**) | 1번째 행 2번째 열에 값을 설정합니다. |
| void [set_Matrix13](./set_matrix13/)(**float**) | 1번째 행 3번째 열에 값을 설정합니다. |
| void [set_Matrix14](./set_matrix14/)(**float**) | 1번째 행 4번째 열에 값을 설정합니다. |
| void [set_Matrix20](./set_matrix20/)(**float**) | 2번째 행 0번째 열에 값을 설정합니다. |
| void [set_Matrix21](./set_matrix21/)(**float**) | 2번째 행 1번째 열에 값을 설정합니다. |
| void [set_Matrix22](./set_matrix22/)(**float**) | 2번째 행 2번째 열에 값을 설정합니다. |
| void [set_Matrix23](./set_matrix23/)(**float**) | 2번째 행 3번째 열에 값을 설정합니다. |
| void [set_Matrix24](./set_matrix24/)(**float**) | 2번째 행 4번째 열에 값을 설정합니다. |
| void [set_Matrix30](./set_matrix30/)(**float**) | 3번째 행 0번째 열에 값을 설정합니다. |
| void [set_Matrix31](./set_matrix31/)(**float**) | 3번째 행 1번째 열에 값을 설정합니다. |
| void [set_Matrix32](./set_matrix32/)(**float**) | 3번째 행 2번째 열에 값을 설정합니다. |
| void [set_Matrix33](./set_matrix33/)(**float**) | 3번째 행 3번째 열에 값을 설정합니다. |
| void [set_Matrix34](./set_matrix34/)(**float**) | 3번째 행 4번째 열에 값을 설정합니다. |
| void [set_Matrix40](./set_matrix40/)(**float**) | 4번째 행 0번째 열에 값을 설정합니다. |
| void [set_Matrix41](./set_matrix41/)(**float**) | 4번째 행 1번째 열에 값을 설정합니다. |
| void [set_Matrix42](./set_matrix42/)(**float**) | 4번째 행 2번째 열에 값을 설정합니다. |
| void [set_Matrix43](./set_matrix43/)(**float**) | 4번째 행 3번째 열에 값을 설정합니다. |
| void [set_Matrix44](./set_matrix44/)(**float**) | 4번째 행 4번째 열에 값을 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 weak 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 weak 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Drawing::Imaging](../)
* 라이브러리 [Aspose.Slides](../../)