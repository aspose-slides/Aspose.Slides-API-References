---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides برای مرجع API C++
description: یک شکل نگهدارنده جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک نمودار SmartArt را نگه دارد.
type: docs
weight: 92
url: /fa/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) متد

یک شکل نگهدارنده جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک نمودار [SmartArt](../../../aspose.slides.smartart/) را نگه دارد.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارنده جدید. |
| y | **float** | مختصات Y شکل نگهدارنده جدید. |
| width | **float** | عرض شکل نگهدارنده جدید. |
| height | **float** | ارتفاع شکل نگهدارنده جدید. |

### مقدار بازگشت

یک [IAutoShape](../../iautoshape/) ایجاد شد با یک [SmartArt](../../../aspose.slides.smartart/) نگهدارنده.

## توضیحات

مثال زیر نشان می‌دهد چطور شکل نگهدارنده [SmartArt](../../../aspose.slides.smartart/) را به اسلاید طرح‌بندی اضافه کنیم. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)