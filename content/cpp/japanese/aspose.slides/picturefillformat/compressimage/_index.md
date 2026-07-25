---
title: CompressImage()
second_title: Aspose.Slides for C++ API リファレンス
description: シェイプのサイズと指定された解像度に基づいて画像のサイズを縮小し、圧縮します。必要に応じて、クロップされた領域も削除します。
type: docs
weight: 443
url: /ja/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) メソッド

画像のサイズをシェイプのサイズと指定された解像度に基づいて縮小し、圧縮します。必要に応じて、クロップされた領域も削除します。

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true の場合、メソッドは画像のクロップされた領域を削除し、サイズをさらに削減する可能性があります。 |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | 圧縮対象の解像度で、[Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) 列挙体の値として指定します。 |

### 戻り値

画像が正常に圧縮されたかどうかを示す **bool**。****true**** を返します。

## 備考

このメソッドは、PowerPoint の「Picture Format -> Compress Pictures」機能と同様に、画像のサイズと解像度を変更します。

画像がリサイズまたはクロップされた場合は ****true****、それ以外は ****false****。

.

以下の例は、対象の解像度を設定し、クロップ領域を削除することで、プレゼンテーション内の画像サイズを縮小する **CompressImage** メソッドの使用方法を示しています:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// 画像をターゲット解像度150 DPI（Web 解像度）で圧縮し、クロップされた領域を削除します
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) メソッド

画像のサイズをシェイプのサイズと指定された解像度に基づいて縮小し、圧縮します。必要に応じて、クロップされた領域も削除します。

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | true の場合、メソッドは画像のクロップされた領域を削除し、サイズをさらに削減する可能性があります。 |
| resolution | **float** | DPI 単位の対象解像度。この値は正でなければならず、画像のリサイズ方法を定義します。 |

### 戻り値

画像が正常に圧縮されたかどうかを示す **bool**。****true**** を返します。

## 備考

このメソッドは、PowerPoint の「Picture Format -> Compress Pictures」機能と同様に、画像のサイズと解像度を変更します。

画像がリサイズまたはクロップされた場合は ****true****、それ以外は ****false****。

.

以下の例は、対象の解像度を設定し、クロップ領域を削除することで、プレゼンテーション内の画像サイズを縮小する **CompressImage** メソッドの使用方法を示しています:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame を取得
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// ターゲット解像度150 DPI（Web 解像度）で画像を圧縮し、クロップされた領域を削除します
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Web 解像度
```

## 参照

* 列挙型 [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* クラス [PictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)