---
title: IControl
second_title: Aspose.Sildes for .NET API Reference
description: 表示一个ActiveX控件。
type: docs
weight: 5430
url: /zh/aspose.slides/icontrol/
---

## IControl 接口

表示一个ActiveX控件。

```csharp
public interface IControl : ISlideComponent
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ActiveXControlBinary](../../aspose.slides/icontrol/activexcontrolbinary) { get; } | 指定使用 PersistStream、PersistStreamInit 或 PersistStorage 方法保存 ActiveX 控件时的持久性。 |
| [AsISlideComponent](../../aspose.slides/icontrol/asislidecomponent) { get; } | 允许获取基础 ISlideComponent 接口。只读 [`ISlideComponent`](../islidecomponent)。 |
| [ClassId](../../aspose.slides/icontrol/classid) { get; } | 获取此控件的类 ID。只读 Guid。 |
| [Frame](../../aspose.slides/icontrol/frame) { get; set; } | 返回或设置控件的框架。读写 [`IShapeFrame`](../ishapeframe)。 |
| [Name](../../aspose.slides/icontrol/name) { get; set; } | 返回此控件的名称。读写 String。 |
| [Persistence](../../aspose.slides/icontrol/persistence) { get; } | 获取用于存储 ActiveX 控件属性的方法。只读 [`PersistenceType`](../persistencetype)。 |
| [Properties](../../aspose.slides/icontrol/properties) { get; } | 返回 ActiveX 属性的集合。只读 [`IControlPropertiesCollection`](../icontrolpropertiescollection)。 |
| [SubstitutePictureFormat](../../aspose.slides/icontrol/substitutepictureformat) { get; } | 返回 ControlEx 图像填充属性对象。只读 [`IPictureFillFormat`](../ipicturefillformat)。 |

### 另请参阅

* 接口 [ISlideComponent](../islidecomponent)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->