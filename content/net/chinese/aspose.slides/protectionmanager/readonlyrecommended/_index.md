---  
title: ReadOnlyRecommended
second_title: Aspose.Sildes for .NET API Reference  
description: 获取或设置只读推荐。可读写的布尔值。
type: docs
weight: 60  
url: /zh/aspose.slides/protectionmanager/readonlyrecommended/
---  

## ProtectionManager.ReadOnlyRecommended property  

获取或设置只读推荐。可读写的布尔值。  

```csharp  
public bool ReadOnlyRecommended { get; set; }  
```  

### Examples  

以下示例代码演示了如何使用 Aspose.Slides 在 C# 中将 PowerPoint 演示文稿设置为只读。  

```csharp  
[C#]  
using (Presentation pres = new Presentation())  
{  
	pres.ProtectionManager.ReadOnlyRecommended = true;  
	pres.Save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);  
}  
```  

### See Also  

* class [ProtectionManager](../../protectionmanager)  
* namespace [Aspose.Slides](../../protectionmanager)  
* assembly [Aspose.Slides](../../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->