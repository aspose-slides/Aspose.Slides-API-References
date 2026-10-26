---
title: Bitmap
second_title: Aspose.Slides for C++ API 참조
description: "GDI+ 비트맵 이미지를 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여만 할당해야 합니다. 스택에 직접 인스턴스를 생성하거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 1
url: /ko/system.drawing/bitmap/
---
## Bitmap 클래스

GDI+ 비트맵 이미지를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 직접 생성하거나 operator new를 사용해서 인스턴스를 만들면 런타임 오류 및/또는 어설션 오류가 발생합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고 이 포인터를 함수 인수로 전달하십시오.

```cpp
class Bitmap : public System::Drawing::Image
```

## 메서드

| Method | Description |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | 픽셀 처리 모드를 활성화합니다. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | [Bitmap](./) 객체를 지정된 기존 이미지에서 새로 생성합니다. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | [Bitmap](./) 객체를 지정된 스트림에서 새로 생성합니다. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | [Bitmap](./) 객체를 지정된 파일에서 새로 생성합니다. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | [Bitmap](./) 객체를 지정된 파일에서 새로 생성합니다. |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | [Bitmap](./) 객체를 지정된 너비, 높이, 픽셀 형식 및 픽셀 데이터를 갖는 비트맵 이미지로 생성합니다. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | [Bitmap](./) 객체를 지정된 기존 이미지에서 지정된 크기로 스케일링하여 새로 생성합니다. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | [Bitmap](./) 객체를 지정된 기존 이미지에서 너비와 높이를 지정된 값으로 스케일링하여 새로 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | 현재 객체의 복사본을 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | [Bitmap](./) 객체를 현재 객체가 나타내는 비트맵 이미지의 영역 복사본으로 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | [Bitmap](./) 객체를 현재 객체가 나타내는 비트맵 이미지의 영역 복사본으로 생성합니다. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | SHA1 해시 값을 계산합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | 지정된 비트맵 이미지의 픽셀 형식을 Format32bppArgb로 변경한 복사본을 생성합니다. |
| void [Dispose](../image/dispose/)() override | 현재 객체가 획득한 모든 리소스를 해제합니다. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | 픽셀 처리 모드를 비활성화합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하다고 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 (NaN 포함) 같지 않지만, 두 NaN을 동일하다고 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | [Image](../image/) 객체를 지정된 파일에서 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | 지정된 GDI 비트맵에서 [Bitmap](./) 객체를 생성합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | 지정된 스트림에서 [Image](../image/) 객체를 생성합니다. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | 이미지의 속성을 나타내는 ImageFlags 열거형 값들의 비트별 조합을 반환합니다. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | 현재 객체가 나타내는 이미지 내 프레임 차원을 나타내는 GUID 배열을 반환합니다. |
| int [get_Height](./get_height/)() const override | 이미지의 높이를 픽셀 단위로 반환합니다. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | 현재 객체가 나타내는 이미지의 가로 해상도를 인치당 픽셀(PPI)로 반환합니다. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | 현재 객체가 나타내는 이미지에 사용된 컬러 팔레트를 반환합니다. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | 현재 객체가 나타내는 이미지의 픽셀 형식을 반환합니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | 이 이미지에 저장된 속성 항목들의 ID를 가져옵니다. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | 이 이미지에 저장된 모든 속성 항목(메타데이터 조각)을 가져옵니다. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | 현재 객체가 나타내는 이미지의 파일 형식을 반환합니다. |
| [Size](../size/) [get_Size](../image/get_size/)() const | 이미지의 너비와 높이를 픽셀 단위로 나타내는 [Size](../size/) 객체를 반환합니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | 이미지에 대한 추가 데이터를 제공하는 객체를 가져옵니다. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | 현재 객체가 나타내는 이미지의 세로 해상도를 인치당 픽셀(PPI)로 반환합니다. |
| int [get_Width](./get_width/)() const override | 이미지의 너비를 픽셀 단위로 반환합니다. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | 지정된 측정 단위로 이미지 경계를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | 지정된 프레임 차원의 프레임 수를 반환합니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 활성화합니다. |
| IntPtr [GetHbitmap](./gethbitmap/)() | 현재 객체가 나타내는 비트맵에서 GDI 비트맵 객체를 생성합니다. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | 지정된 픽셀의 색상을 반환합니다. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | 지정된 픽셀 형식에서 색 깊이를 표현하는 데 사용되는 비트 수를 반환합니다. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | 기본 SkBitmap 객체에 대한 원시 포인터를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | 이 [System::Drawing::Image](../image/) 객체에 대한 썸네일을 가져옵니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | 지정된 픽셀 형식에 알파 정보가 포함되어 있는지 판단합니다. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | 원본 형식이 다중 이미지인지 여부를 반환합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금 기능을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | [Bitmap](./) 를 시스템 메모리에 잠급니다. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | [Bitmap](./) 를 시스템 메모리에 잠급니다. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | 지정된 색상의 모든 픽셀 색상을 투명하게 변경합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 활성화합니다. |
| [Object](../../system/object/object/)() | 객체를 생성하고 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 구성을 가능하게 합니다. |
| void [PremultipleColors](./premultiplecolors/)() | 현재 객체가 나타내는 이미지 픽셀의 색상을 사전 곱합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조에 의해 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값형 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | 이미지를 90도 배수만큼 회전하고 뒤집습니다. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | 현재 객체가 나타내는 이미지를 PNG 형식으로 지정된 파일에 저장합니다. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | 현재 객체가 나타내는 이미지를 지정된 형식으로 지정된 파일에 저장합니다. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | 현재 객체가 나타내는 이미지를 지정된 형식으로 지정된 스트림에 저장합니다. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | 현재 객체가 나타내는 이미지를 지정된 인코더와 인코더 매개변수를 사용하여 지정된 파일에 저장합니다. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | 현재 객체가 나타내는 이미지를 지정된 인코더와 인코더 매개변수를 사용하여 지정된 스트림에 저장합니다. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](../image/save/) 메서드의 이전 호출에서 지정된 파일 또는 스트림에 프레임을 추가합니다. |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](../image/save/) 메서드의 이전 호출에서 지정된 파일 또는 스트림에 프레임을 추가합니다. |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | 지정된 프레임을 선택합니다. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | 현재 객체가 나타내는 이미지에 사용되는 컬러 팔레트를 설정합니다. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 이미지에 대한 추가 데이터를 제공하는 객체를 설정합니다. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | 현재 객체가 나타내는 비트맵 이미지에서 지정된 픽셀의 색상을 설정합니다. |
| void [SetResolution](./setresolution/)(**float**, **float**) | 이미지의 해상도를 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 템플릿의 n번째 인수를 공유가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 공유 참조 카운터의 현재 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 해제하는 기능을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | 지정된 비트맵을 시스템 메모리에서 해제합니다. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하지 말고 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴하고 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Image](../image/)
* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)