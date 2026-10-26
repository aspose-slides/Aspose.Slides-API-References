---
title: GetEffective()
second_title: Aspose.Slides for C++ API 参考
description: 获取在应用继承后的有效项目符号格式化数据。
type: docs
weight: 248
url: /zh/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() 方法


获取应用继承后的有效项目符号格式化数据。

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```


### 返回值

一个 [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## 备注



此示例演示获取一些有效的项目符号格式属性。 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* 类 [IBulletFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)