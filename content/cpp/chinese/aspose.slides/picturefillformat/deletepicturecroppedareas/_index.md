---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides for C++ API 参考
description: 删除填充图片的裁剪区域。
type: docs
weight: 430
url: /zh/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() 方法


删除填充 [Picture](../../picture/) 的裁剪区域。
```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```


### 返回值

裁剪后的图像，如果不需要裁剪则返回原始图像。
## 备注


此方法在裁剪时将 WMF/EMF 元文件转换为栅格 PNG 图像。

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// 获取 PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// 删除 PictureFrame 图像的裁剪区域
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPPImage](../../ippimage/)
* 类 [PictureFillFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)