---
title: GetEffective()
second_title: Aspose.Slides C++ API 参考
description: 获取应用继承后的有效文本样式格式化数据。
type: docs
weight: 27
url: /zh/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() 方法


获取应用继承后的有效文本样式格式化数据。

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### 返回值

一个 [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## 备注



本示例演示了获取部分有效文本样式属性。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* 类 [TextStyle](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)