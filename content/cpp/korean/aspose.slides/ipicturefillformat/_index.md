---
title: IPictureFillFormat
second_title: Aspose.Slides for C++ API 레퍼런스
description: 그림 채우기 스타일을 나타냅니다.
type: docs
weight: 3225
url: /ko/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat 클래스

그림 채우기 스타일을 나타냅니다.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## 메서드

| Method | Description |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | 이미지를 도형 크기와 지정된 해상도를 기반으로 크기를 줄여 압축합니다. 선택적으로 잘린 영역도 삭제합니다. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | 이미지를 도형 크기와 지정된 해상도를 기반으로 크기를 줄여 압축합니다. 선택적으로 잘린 영역도 삭제합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | 채우기 [Picture](../picture/)의 잘린 영역을 삭제합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 타입 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T1 const\&) | C# 스타일로 값 타입 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이션합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# 스타일 부동 소수점 비교를 에뮬레이션합니다. 두 NaN이 IEC 60559:1989에 따르면 NaN은 어떤 값과도(NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | 그림의 아래쪽에서 잘려 나가는 실제 이미지 높이의 백분율을 반환합니다. 읽기 **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | 그림의 왼쪽에서 잘려 나가는 실제 이미지 너비의 백분율을 반환합니다. 읽기 **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | 그림의 오른쪽에서 잘려 나가는 실제 이미지 너비의 백분율을 반환합니다. 읽기 **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | 그림의 위쪽에서 잘려 나가는 실제 이미지 높이의 백분율을 반환합니다. 읽기 **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | 그림을 채우는 데 사용되는 dpi를 반환합니다. 읽기 **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | 그림을 반환합니다. 읽기 전용 [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | 그림 채우기 모드를 반환합니다. 읽기 [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | 도형 경계 상자의 아래쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 아래쪽 가장자리를 반환합니다. 양의 백분율은 내부 여백을, 음의 백분율은 외부 여백을 지정합니다. 읽기 **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | 도형 경계 상자의 왼쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자를 반환합니다. 양의 백분율은 내부 여백을, 음의 백분율은 외부 여백을 지정합니다. 읽기 **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | 도형 경계 상자의 오른쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 반환합니다. 양의 백분율은 내부 여백을, 음의 백분율은 외부 여백을 지정합니다. 읽기 **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | 도형 경계 상자의 위쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 위쪽 가장자를 반환합니다. 양의 백분율은 내부 여백을, 음의 백분율은 외부 여백을 지정합니다. 읽기 **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | 텍스처가 도형 내에서 정렬되는 방식을 반환합니다. 이 설정은 텍스처 패턴의 시작점과 도형 전체에 걸친 반복 방식을 제어합니다. 읽기 [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | 텍스처 타일을 수평, 수직 또는 두 축 모두에 대해 뒤집습니다. 읽기 [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | 텍스처가 도형 원점으로부터 포인트 단위로 이동한 수평 오프셋을 반환합니다. 양수 값은 텍스처를 오른쪽으로 이동시키고, 음수 값은 왼쪽으로 이동시킵니다. 읽기 **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | 텍스처가 도형 원점으로부터 포인트 단위로 이동한 수직 오프셋을 반환합니다. 양수 값은 텍스처를 아래쪽으로 이동시키고, 음수 값은 위쪽으로 이동시킵니다. 읽기 **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | 텍스처 채우기의 수평 스케일을 백분율로 반환합니다. 읽기 **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | 텍스처 채우기의 수직 스케일을 백분율로 반환합니다. 읽기 **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 경비 객체를 사용하세요. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무것도 복사하지 않으며, 새로운 객체를 초기화하고 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 타입 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | 그림의 아래쪽에서 잘려 나가는 실제 이미지 높이의 백분율을 설정합니다. 쓰기 **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | 그림의 왼쪽에서 잘려 나가는 실제 이미지 너비의 백분율을 설정합니다. 쓰기 **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | 그림의 오른쪽에서 잘려 나가는 실제 이미지 너비의 백분율을 설정합니다. 쓰기 **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | 그림의 위쪽에서 잘려 나가는 실제 이미지 높이의 백분율을 설정합니다. 쓰기 **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | 그림을 채우는 데 사용되는 dpi를 설정합니다. 쓰기 **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | 그림 채우기 모드를 설정합니다. 쓰기 [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | 도형 경계 상자의 아래쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 아래쪽 가장자를 설정합니다. 양의 백분율은 내부 여백을, 음의 백분율은 외부 여백을 지정합니다. 쓰기 **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | 도형 경계 상자의 왼쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자를 설정합니다. 양의 백분율은 내부 여백을, 음의 백분율은 외부 여백을 지정합니다. 쓰기 **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | 도형 경계 상자의 오른쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 설정합니다. 양의 백분율은 내부 여백을, 음의 백분율은 외부 여백을 지정합니다. 쓰기 **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | 도형 경계 상자의 위쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 위쪽 가장자를 설정합니다. 양의 백분율은 내부 여백을, 음의 백분율은 외부 여백을 지정합니다. 쓰기 **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | 텍스처가 도형 내에서 정렬되는 방식을 설정합니다. 이 설정은 텍스처 패턴의 시작점과 도형 전체에 걸친 반복 방식을 제어합니다. 쓰기 [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | 텍스처 타일을 수평, 수직 또는 두 축 모두에 대해 뒤집습니다. 쓰기 [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | 텍스처가 도형 원점으로부터 포인트 단위로 이동한 수평 오프셋을 설정합니다. 양수 값은 텍스처를 오른쪽으로 이동시키고, 음수 값은 왼쪽으로 이동시킵니다. 쓰기 **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | 텍스처가 도형 원점으로부터 포인트 단위로 이동한 수직 오프셋을 설정합니다. 양수 값은 텍스처를 아래쪽으로 이동시키고, 음수 값은 위쪽으로 이동시킵니다. 쓰기 **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | 텍스처 채우기의 수평 스케일을 백분율로 설정합니다. 쓰기 **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | 텍스처 채우기의 수직 스케일을 백분율로 설정합니다. 쓰기 **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너 내 포인터를 약한 모드로 전환할 수 있게 합니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 레퍼런스 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 경비 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참고

* 클래스 [IFillParamSource](../ifillparamsource/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)