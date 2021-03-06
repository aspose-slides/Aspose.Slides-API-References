---
title: GetEffective
second_title: Aspose.Slides for .NET API 参考
description: 获取有效的 3-D 格式化数据并应用继承
type: docs
weight: 110
url: /zh/net/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat.GetEffective method

获取有效的 3-D 格式化数据并应用继承。

```csharp
public IThreeDFormatEffectiveData GetEffective()
```

### 返回值

一个[`IThreeDFormatEffectiveData`](../../ithreedformateffectivedata).

### 例子

这个例子演示了如何为相机、灯光装置和形状的顶部斜角获取有效的属性。

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    IThreeDFormatEffectiveData threeDEffectiveData = pres.Slides[0].Shapes[0].ThreeDFormat.GetEffective();

    Console.WriteLine("= Effective camera properties =");
    Console.WriteLine("Type: " + threeDEffectiveData.Camera.CameraType);
    Console.WriteLine("Field of view: " + threeDEffectiveData.Camera.FieldOfViewAngle);
    Console.WriteLine("Zoom: " + threeDEffectiveData.Camera.Zoom);

    Console.WriteLine("= Effective light rig properties =");
    Console.WriteLine("Type: " + threeDEffectiveData.LightRig.LightType);
    Console.WriteLine("Direction: " + threeDEffectiveData.LightRig.Direction);

    Console.WriteLine("= Effective shape's top face relief properties =");
    Console.WriteLine("Type: " + threeDEffectiveData.BevelTop.BevelType);
    Console.WriteLine("Width: " + threeDEffectiveData.BevelTop.Width);
    Console.WriteLine("Height: " + threeDEffectiveData.BevelTop.Height);
}
```

### 也可以看看

* interface [IThreeDFormatEffectiveData](../../ithreedformateffectivedata)
* class [ThreeDFormat](../../threedformat)
* 命名空间 [Aspose.Slides](../../threedformat)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
