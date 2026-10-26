---
title: Bitmap()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 기존 이미지에서 새 Bitmap 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) 생성자

지정된 기존 이미지에서 새 [Bitmap](../) 객체를 생성합니다.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 비트맵 이미지를 생성하기 위해 사용되는 기존 이미지 |
|  |  |  |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) 생성자

지정된 스트림에서 새 [Bitmap](../) 객체를 생성합니다.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 이미지 데이터를 포함하는 스트림 |
| useIcm | **bool** | 무시 |

## Bitmap::Bitmap(const String\&) 생성자

지정된 파일에서 새 [Bitmap](../) 객체를 생성합니다.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 이미지 데이터를 포함하는 파일 이름 |

## Bitmap::Bitmap(const String\&, bool) 생성자

지정된 파일에서 새 [Bitmap](../) 객체를 생성합니다.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 이미지 데이터를 포함하는 파일 이름 |
| useIcm | **bool** | 무시 |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) 생성자

지정된 너비, 높이, 픽셀 형식 및 픽셀 데이터를 갖는 새 [Bitmap](../) 객체를 생성합니다.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | int | 이미지의 너비 |
| height | int | 이미지의 높이 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 이미지의 픽셀 형식 |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) 생성자

지정된 기존 이미지를 지정된 크기로 스케일링하여 새 [Bitmap](../) 객체를 생성합니다.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 비트맵 이미지를 생성하기 위해 사용되는 기존 이미지 |
| size | const [Size](../../size/)\& | 새 이미지의 크기 |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) 생성자

지정된 기존 이미지를 지정된 너비와 높이로 스케일링하여 새 [Bitmap](../) 객체를 생성합니다.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 비트맵 이미지를 생성하기 위해 사용되는 기존 이미지 |
| width | int | 새 이미지의 너비 |
| height | int | 새 이미지의 높이 |

## 참고

* 열거형 [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Image](../../image/)
* 클래스 [Bitmap](../)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [String](../../../system/string/)
* 클래스 [Size](../../size/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)