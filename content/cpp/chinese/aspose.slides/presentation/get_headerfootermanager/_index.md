---
title: get_HeaderFooterManager()
second_title: Aspose.Slides C++ API 参考
description: 返回实际的 HeaderFooter manager。只读 IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /zh/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() 方法


返回实际的 HeaderFooter manager。只读 [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)。

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## 备注


下面的示例展示了如何在 PowerPoint [Presentation](../) 的 [Slide](../../slide/) 中设置页脚的可见性。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// 属性 IsFooterVisible 用于指示幻灯片页脚占位符不存在。
if (!headerFooterManager->get_IsFooterVisible())
{
    // 方法 SetFooterVisibility 用于使幻灯片页脚占位符可见。
    headerFooterManager->SetFooterVisibility(true);
}

// 属性 IsSlideNumberVisible 用于指示幻灯片页码占位符不存在。
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // 方法 SetSlideNumberVisibility 用于使幻灯片页码占位符可见。
    headerFooterManager->SetSlideNumberVisibility(true);
}

// 属性 IsDateTimeVisible 用于指示幻灯片日期时间占位符不存在。
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // 方法 SetFooterVisibility 用于使幻灯片日期时间占位符可见。
    headerFooterManager->SetDateTimeVisibility(true);
}

// 方法 SetFooterText 用于设置幻灯片页脚占位符的文本。
headerFooterManager->SetFooterText(u"Footer text");
// 方法 SetDateTimeText 用于设置幻灯片日期时间占位符的文本。
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
下面的示例展示了如何在 [Slide](../../slide/) 中设置子页脚的可见性。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// 方法 SetFooterAndChildFootersVisibility 用于使母版幻灯片及所有子页脚占位符可见。
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// 方法 SetSlideNumberAndChildSlideNumbersVisibility 用于使母版幻灯片及所有子页码占位符可见。
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// 方法 SetDateTimeAndChildDateTimesVisibility 用于使母版幻灯片及所有子日期时间占位符可见。
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// 方法 SetFooterAndChildFootersText 用于设置母版幻灯片及所有子页脚占位符的文本。
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// 方法 SetDateTimeAndChildDateTimesText 用于设置母版幻灯片及所有子日期时间占位符的文本。
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)