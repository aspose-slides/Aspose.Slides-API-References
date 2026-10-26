---
title: PictureFillFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 그림 채우기 스타일을 나타냅니다.
type: docs
weight: 4720
url: /ko/aspose.slides/picturefillformat/
---
## PictureFillFormat 클래스

Represents a picture fill style.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | 이미지를 도형 크기와 지정된 해상도에 기반하여 크기를 줄여 압축합니다. 선택적으로 잘라낸 영역을 삭제합니다. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | 이미지를 도형 크기와 지정된 해상도에 기반하여 크기를 줄여 압축합니다. 선택적으로 잘라낸 영역을 삭제합니다. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | 채우기 [Picture](../picture/)의 잘라낸 영역을 삭제합니다. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 지정된 객체와 비교합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미론을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| **float** [get_CropBottom](./get_cropbottom/)() override | 그림 하단에서 잘라낸 실제 이미지 높이의 백분율을 반환합니다. 읽기 **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | 그림 왼쪽에서 잘라낸 실제 이미지 너비의 백분율을 반환합니다. 읽기 **float**. |
| **float** [get_CropRight](./get_cropright/)() override | 그림 오른쪽에서 잘라낸 실제 이미지 너비의 백분율을 반환합니다. 읽기 **float**. |
| **float** [get_CropTop](./get_croptop/)() override | 그림 상단에서 잘라낸 실제 이미지 높이의 백분율을 반환합니다. 읽기 **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | 그림을 채우는 데 사용되는 dpi를 반환합니다. 읽기 **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate 객체를 반환합니다. 읽기 전용 [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 부모 [IPresentationComponent](../ipresentationcomponent/)를 반환합니다. 읽기 전용 [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | 그림을 반환합니다. 읽기 전용 [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | 그림 채우기 모드를 반환합니다. 읽기 [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | 도형 경계 상자의 하단 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 하단 가장자를 반환합니다. 양수 백분율은 안쪽 여백을, 음수 백분율은 바깥쪽 여백을 나타냅니다. 읽기 **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | 도형 경계 상자의 왼쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자를 반환합니다. 양수 백분율은 안쪽 여백을, 음수 백분율은 바깥쪽 여백을 나타냅니다. 읽기 **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | 도형 경계 상자의 오른쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 반환합니다. 양수 백분율은 안쪽 여백을, 음수 백분율은 바깥쪽 여백을 나타냅니다. 읽기 **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | 도형 경계 상자의 상단 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 상단 가장자를 반환합니다. 양수 백분율은 안쪽 여백을, 음수 백분율은 바깥쪽 여백을 나타냅니다. 읽기 **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | 텍스처가 도형 안에서 정렬되는 방식을 반환합니다. 이 설정은 텍스처 패턴의 시작 위치와 도형 전체에 반복되는 방식을 제어합니다. 읽기 [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | 텍스처 타일을 수평, 수직 또는 두 축 모두를 기준으로 뒤집습니다. 읽기 [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | 도형 원점으로부터 텍스처의 수평 오프셋을 포인트 단위로 반환합니다. 양수 값은 텍스처를 오른쪽으로, 음수 값은 왼쪽으로 이동시킵니다. 읽기 **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | 도형 원점으로부터 텍스처의 수직 오프셋을 포인트 단위로 반환합니다. 양수 값은 텍스처를 아래로, 음수 값은 위로 이동시킵니다. 읽기 **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | 텍스처 채우기의 수평 스케일을 백분율로 반환합니다. 읽기 **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | 텍스처 채우기의 수직 스케일을 백분율로 반환합니다. 읽기 **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 해시 코드를 반환합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금입니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 활성화합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | 그림 하단에서 잘라낸 실제 이미지 높이의 백분율을 설정합니다. 쓰기 **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | 그림 왼쪽에서 잘라낸 실제 이미지 너비의 백분율을 설정합니다. 쓰기 **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | 그림 오른쪽에서 잘라낸 실제 이미지 너비의 백분율을 설정합니다. 쓰기 **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | 그림 상단에서 잘라낸 실제 이미지 높이의 백분율을 설정합니다. 쓰기 **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | 그림을 채우는 데 사용되는 dpi를 설정합니다. 쓰기 **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | 그림 채우기 모드를 설정합니다. 쓰기 [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | 도형 경계 상자의 하단 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 하단 가장자를 설정합니다. 양수 백분율은 안쪽 여백을, 음수 백분율은 바깥쪽 여백을 나타냅니다. 쓰기 **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | 도형 경계 상자의 왼쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자를 설정합니다. 양수 백분율은 안쪽 여백을, 음수 백분율은 바깥쪽 여백을 나타냅니다. 쓰기 **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | 도형 경계 상자의 오른쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 설정합니다. 양수 백분율은 안쪽 여백을, 음수 백분율은 바깥쪽 여백을 나타냅니다. 쓰기 **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | 도형 경계 상자의 상단 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 상단 가장자를 설정합니다. 양수 백분율은 안쪽 여백을, 음수 백분율은 바깥쪽 여백을 나타냅니다. 쓰기 **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | 텍스처가 도형 안에서 정렬되는 방식을 설정합니다. 이 설정은 텍스처 패턴의 시작 위치와 도형 전체에 반복되는 방식을 제어합니다. 쓰기 [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | 텍스처 타일을 수평, 수직 또는 두 축 모두를 기준으로 뒤집습니다. 쓰기 [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | 도형 원점으로부터 텍스처의 수평 오프셋을 포인트 단위로 설정합니다. 양수 값은 텍스처를 오른쪽으로, 음수 값은 왼쪽으로 이동시킵니다. 쓰기 **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | 도형 원점으로부터 텍스처의 수직 오프셋을 포인트 단위로 설정합니다. 양수 값은 텍스처를 아래로, 음수 값은 위로 이동시킵니다. 쓰기 **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | 텍스처 채우기의 수평 스케일을 백분율로 설정합니다. 쓰기 **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | 텍스처 채우기의 수직 스케일을 백분율로 설정합니다. 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [PVIObject](../pviobject/)
* 클래스 [IPictureFillFormat](../ipicturefillformat/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)