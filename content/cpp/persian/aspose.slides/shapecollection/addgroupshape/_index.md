---
title: AddGroupShape()
second_title: مرجع API Aspose.Slides برای C++
description: یک شکل گروه خالی جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید. چارچوب گروه به طور خودکار تنظیم می‌شود تا هر شکلی که به آن اضافه شود، سازگار باشد.
type: docs
weight: 391
url: /fa/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() متد

یک شکل گروه خالی جدید ایجاد می‌کند و آن را به انتهای مجموعه اشکال اضافه می‌نماید. چارچوب گروه به‌طور خودکار تنظیم می‌شود تا هر شکلی که به آن اضافه شود، سازگار باشد.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### مقدار بازگشت

[IGroupShape](../../igroupshape/) جدیداً ایجاد شده.

## توضیحات

مثال زیر نشان می‌دهد که چگونه یک شکل گروهی را به یک اسلاید PowerPoint [Presentation](../../presentation/) اضافه کنید.

```cpp
// نمونه‌سازی کلاس Presentation
auto pres = System::MakeObject<Presentation>();

// دریافت اولین اسلاید
auto slide = pres->get_Slides()->idx_get(0);
// دسترسی به مجموعه اشکال اسلایدها
auto slideShapes = slide->get_Shapes();
// افزودن یک شکل گروهی به اسلاید
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// افزودن اشکال داخل شکل گروهی اضافه‌شده
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// افزودن چارچوب شکل گروهی
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// نوشتن فایل PPTX به دیسک
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) متد

یک شکل گروهی جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به شکل‌های جداگانه تبدیل می‌نماید، و گروه حاصل را به انتهای مجموعه اشکال اضافه می‌کند.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) شامل محتوای برداری برای تبدیل به شکل‌ها. |
| x | **float** | مختصات x چارچوب گروه، بر حسب نقطه. |
| y | **float** | مختصات y چارچوب گروه، بر حسب نقطه. |
| width | **float** | عرض چارچوب گروه، بر حسب نقطه. |
| height | **float** | ارتفاع چارچوب گروه، بر حسب نقطه. |

### مقدار بازگشت

[IGroupShape](../../igroupshape/) جدیداً ایجاد شده.

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IGroupShape](../../igroupshape/)
* کلاس [ShapeCollection](../)
* کلاس [ISvgImage](../../isvgimage/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)