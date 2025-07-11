---  
title: MasterSlide
second_title: Aspose.Sildes for .NET API Reference  
description: 遍历每个 MasterSlide aspose.slides.lowcode/foreach/masterslide 在 Presentation aspose.slides/presentation 中。
type: docs
weight: 20  
url: /zh/aspose.slides.lowcode/foreach/masterslide/
---  
  
## ForEach.MasterSlide 方法  
  
遍历 [`Presentation`](../../../aspose.slides/presentation) 中的每个 `MasterSlide`。  
  
```csharp  
public static void MasterSlide(Presentation pres, ForEachMasterSlideCallback forEachMasterSlide)  
```  
  
| 参数 | 类型 | 描述 |  
| --- | --- | --- |  
| pres | Presentation | 用于遍历母片的演示文稿 |  
| forEachMasterSlide | ForEachMasterSlideCallback | 将为每个母片调用的回调 |  
  
### 示例  
  
```csharp  
using (Presentation pres = new Presentation("pres.pptx"))  
{  
    ForEach.MasterSlide(pres, (slide, index) =>  
    {  
        slide.Name = $"MasterSlide #{index}";  
    });  
}  
```  
  
### 另请参阅  
  
* class [Presentation](../../../aspose.slides/presentation)  
* delegate [ForEachMasterSlideCallback](../../foreach.foreachmasterslidecallback)  
* class [ForEach](../../foreach)  
* namespace [Aspose.Slides.LowCode](../../foreach)  
* assembly [Aspose.Slides](../../../)  
  
<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  