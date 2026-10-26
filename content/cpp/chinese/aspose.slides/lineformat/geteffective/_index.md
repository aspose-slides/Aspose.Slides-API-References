---
title: GetEffective()
second_title: Aspose.Slides for C++ API 参考
description: 获取已应用继承的有效线条格式数据。
type: docs
weight: 417
url: /zh/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() 方法


获取已应用继承的有效线条格式数据。

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### 返回值

一个 [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## 备注



此示例演示如何获取形状的有效线条格式属性。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* 类 [LineFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)