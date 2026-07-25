---
title: DeletePictureCroppedAreas()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 塗りつぶし画像の切り取り領域を削除します。
type: docs
weight: 430
url: /ja/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() method


Fill [Picture](../../picture/) の切り取り領域を削除します。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```


### 戻り値

切り取りが不要な場合は、切り取り画像または元の画像が返されます。

## 備考


このメソッドは、WMF/EMF メタファイルをラスタ PNG 画像に変換しながら、切り取りを行います。



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame を取得します
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// PictureFrame の画像の切り取り領域を削除します
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)