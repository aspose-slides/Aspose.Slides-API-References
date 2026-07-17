---
title: GetEffective()
second_title: Aspose.Slides C++ API 参考
description: 获取已应用继承的有效段落格式数据。
type: docs
weight: 365
url: /zh/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() 方法


获取已应用继承的有效段落格式数据。

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### 返回值

一个 [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)。
## 备注



此示例演示了获取一些有效段落格式属性。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Class [ParagraphFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)