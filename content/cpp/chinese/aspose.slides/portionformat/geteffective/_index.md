---
title: GetEffective()
second_title: Aspose.Slides 的 C++ API 参考
description: 获取在应用继承后的有效部分格式化数据。
type: docs
weight: 131
url: /zh/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() 方法


获取在应用继承后的有效部分格式化数据。

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### 返回值

一个 [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## 备注



此示例演示了获取一些有效部分格式属性。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* 类 [PortionFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)