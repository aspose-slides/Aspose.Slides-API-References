---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /vi/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Callback sẽ được gọi cho mỗi [Slide](../../com.aspose.slides/slide), đường dẫn đầu ra dự kiến sẽ được trả về. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


Callback sẽ được gọi cho mỗi [Slide](../../com.aspose.slides/slide), đường dẫn đầu ra dự kiến sẽ được trả về.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Slide hiện đang được lặp |
| index | int | Chỉ số của slide hiện tại |

**Giá trị trả về:**
java.lang.String