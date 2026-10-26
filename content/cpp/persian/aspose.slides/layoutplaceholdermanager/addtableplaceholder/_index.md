---
title: AddTablePlaceholder()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل نگهدارنده جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک جدول را در خود نگه دارد.
type: docs
weight: 79
url: /fa/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) متد

یک شکل نگهدارنده جدید به اسلاید طرح‌بندی اضافه می‌کند تا یک جدول را در خود نگه دارد.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | **float** | مختصات X شکل نگهدارنده جدید. |
| y | **float** | مختصات Y شکل نگهدارنده جدید. |
| width | **float** | عرض شکل نگهدارنده جدید. |
| height | **float** | ارتفاع شکل نگهدارنده جدید. |

### مقدار بازگشت

یک [IAutoShape](../../iautoshape/) با یک نگهدارنده [Table](../../table/) ایجاد شد.
## توضیحات



مثال زیر نشان می‌دهد چگونه شکل نگهدارنده [Table](../../table/) را به اسلاید طرح‌بندی اضافه کنیم.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAutoShape](../../iautoshape/)
* کلاس [LayoutPlaceholderManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)