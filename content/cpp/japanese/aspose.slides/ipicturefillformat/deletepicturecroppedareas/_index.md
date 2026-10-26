---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 塗りつぶし画像の切り取られた領域を削除します。
type: docs
weight: 430
url: /ja/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() メソッド


フィル [Picture](../../picture/) の切り取られた領域を削除します。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### 戻り値

切り取られた画像、または切り取りが不要な場合は元の画像です。
## 備考


このメソッドは、切り取り中に WMF/EMF メタファイルをラスター PNG 画像に変換します。



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// PictureFrame を取得します
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// PictureFrame 画像の切り取られた領域を削除します
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPPImage](../../ippimage/)
* クラス [IPictureFillFormat](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)