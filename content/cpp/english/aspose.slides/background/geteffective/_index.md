---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective background data with the inheritance applied.
type: docs
weight: 118
url: /aspose.slides/background/geteffective/
---
## Background::GetEffective() method


Gets effective background data with the inheritance applied.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Return Value

A [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Remarks



This example demonstrates getting effective background properties. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Class [Background](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)