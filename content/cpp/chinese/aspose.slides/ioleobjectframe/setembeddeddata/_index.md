---
title: SetEmbeddedData()
second_title: Aspose.Slides C++ API 参考
description: 设置 OLE 嵌入数据的信息。
type: docs
weight: 248
url: /zh/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) 方法

设置 OLE 嵌入数据的信息。

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | 嵌入数据 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## 备注

此方法更改对象的属性以反映新数据，并将 IsObjectLink 标志设置为 false，指示该 OLE 对象为嵌入对象。

下面的示例演示了如何更改现有 [IOleObjectFrame](../) 对象的 OLE 嵌入数据及其类型。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* 类 [IOleObjectFrame](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)