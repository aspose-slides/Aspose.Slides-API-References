---  
title: ExportHiddenSlides
second_title: Aspose.Sildes for .NET API Reference  
description: 确定隐藏幻灯片是否会被导出。
type: docs
weight: 20  
url: /zh/aspose.slides.export.xaml/xamloptions/exporthiddenslides/
---  

## XamlOptions.ExportHiddenSlides 属性  

确定隐藏幻灯片是否会被导出。  

```csharp  
public bool ExportHiddenSlides { get; set; }  
```  

### 示例  

```csharp  
[C#]  
using (Presentation pres = new Presentation("pres.pptx"))  
{  
	pres.Save(new XamlOptions { ExportHiddenSlides = true });  
}  
```  

### 另请参阅  

* class [XamlOptions](../../xamloptions)  
* namespace [Aspose.Slides.Export.Xaml](../../xamloptions)  
* assembly [Aspose.Slides](../../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  