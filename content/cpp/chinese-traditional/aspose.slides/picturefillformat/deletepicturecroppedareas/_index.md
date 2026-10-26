---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides for C++ API 參考
description: 刪除填充圖片的裁剪區域。
type: docs
weight: 430
url: /zh-hant/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() 方法

刪除填充 [Picture](../../picture/) 的裁剪區域。

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### 返回值

如果不需要裁剪，則返回裁剪後的圖像或原始圖像。

## 備註

此方法在裁剪時將 WMF/EMF 中繼檔轉換為光柵 PNG 圖像。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 取得 PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// 刪除 PictureFrame 圖像的裁剪區域
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPPImage](../../ippimage/)
* 類別 [PictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)