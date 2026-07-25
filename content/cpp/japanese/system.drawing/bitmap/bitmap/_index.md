---
title: Bitmap()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された既存の画像から新しい Bitmap オブジェクトを作成します。
type: docs
weight: 1
url: /ja/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) コンストラクタ

指定された既存の画像から新しい [Bitmap](../) オブジェクトを作成します。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ビットマップ画像を作成する元となる既存の画像 |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) コンストラクタ

指定されたストリームから新しい [Bitmap](../) オブジェクトを作成します。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 画像データを含むストリーム |
| useIcm | **bool** | 無視されます |

## Bitmap::Bitmap(const String\&) コンストラクタ

指定されたファイルから新しい [Bitmap](../) オブジェクトを作成します。

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 画像データを含むファイルの名前 |

## Bitmap::Bitmap(const String\&, bool) コンストラクタ

指定されたファイルから新しい [Bitmap](../) オブジェクトを作成します。

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 画像データを含むファイルの名前 |
| useIcm | **bool** | 無視されます |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) コンストラクタ

指定された幅・高さ・ピクセル形式およびピクセルデータでビットマップ画像を表す新しい [Bitmap](../) オブジェクトを作成します。

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | int | 画像の幅 |
| height | int | 画像の高さ |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 画像のピクセル形式 |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) コンストラクタ

指定された既存の画像を指定されたサイズにスケーリングして新しい [Bitmap](../) オブジェクトを作成します。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ビットマップ画像を作成する元となる既存の画像 |
| size | const [Size](../../size/)\& | 新しい画像のサイズ |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) コンストラクタ

指定された既存の画像を幅と高さが指定された値にスケーリングして新しい [Bitmap](../) オブジェクトを作成します。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ビットマップ画像を作成する元となる既存の画像 |
| width | int | 新しい画像の幅 |
| height | int | 新しい画像の高さ |

## 参照

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)