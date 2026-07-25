---
title: CompressImage()
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプのサイズと指定された解像度に基づいて画像のサイズを縮小し、圧縮します。オプションで、切り取られた領域も削除します。
type: docs
weight: 443
url: /ja/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) メソッド

画像を、シェイプのサイズと指定された解像度に基づいてサイズを縮小することで圧縮します。オプションで、切り取られた領域も削除します。

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true の場合、メソッドは画像の切り取られた領域を削除し、サイズをさらに縮小する可能性があります。 |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | 圧縮の対象となる解像度で、[Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) 列挙体の値として指定されます。 |

### 戻り値

画像が正常に圧縮されたかどうかを示す **bool**。****true**** を返します。

## 備考

このメソッドは、PowerPoint の「Picture Format -> Compress Pictures」機能と同様に、画像のサイズと解像度を変更します。

画像がリサイズまたはクロップされた場合は true、そうでなければ ****false****

.

次の例は、対象の解像度を設定し、切り取られた領域を削除することで、プレゼンテーション内の画像サイズを縮小する **CompressImage** メソッドの使用方法を示します：
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// 画像を目標解像度150 DPI（Web 解像度）で圧縮し、切り取られた領域を削除します
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) メソッド

画像を、シェイプのサイズと指定された解像度に基づいてサイズを縮小することで圧縮します。オプションで、切り取られた領域も削除します。

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true の場合、メソッドは画像の切り取られた領域を削除し、サイズをさらに縮小する可能性があります。 |
| resolution | **float** | DPI 単位の対象解像度。この値は正でなければならず、画像のリサイズ方法を定義します。 |

### 戻り値

画像が正常に圧縮されたかどうかを示す **bool**。****true**** を返します。

## 備考

このメソッドは、PowerPoint の「Picture Format -> Compress Pictures」機能と同様に、画像のサイズと解像度を変更します。

画像がリサイズまたはクロップされた場合は true、そうでなければ ****false****

.

次の例は、対象の解像度を設定し、切り取られた領域を削除することで、プレゼンテーション内の画像サイズを縮小する **CompressImage** メソッドの使用方法を示します：
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame を取得します
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// 画像を目標解像度150 DPI（Web 解像度）で圧縮し、切り取られた領域を削除します
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Web 解像度
```

## 参照

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)