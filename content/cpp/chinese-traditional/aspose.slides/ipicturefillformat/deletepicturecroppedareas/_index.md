---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides for C++ API 參考
description: 刪除填充圖片的裁切區域。
type: docs
weight: 430
url: /zh-hant/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() 方法


刪除填充 [Picture](../../picture/) 的裁切區域。

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### 返回值

若不需要裁切，則返回裁切後的圖像或原始圖像。

## 備註


此方法在裁切的同時，將 WMF/EMF 中繪圖檔轉換為點陣 PNG 圖像。



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Deletes cropped areas of the PictureFrame image
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPPImage](../../ippimage/)
* 類別 [IPictureFillFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)