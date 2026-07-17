---
title: GetEffective()
second_title: Aspose.Slides C++ API 参考
description: 获取已应用继承的有效背景数据。
type: docs
weight: 118
url: /zh/aspose.slides/background/geteffective/
---
## Background::GetEffective() 方法


获取已应用继承的有效背景数据。

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### 返回值

一个 [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## 备注



此示例演示了获取有效的背景属性。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* 类 [Background](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)