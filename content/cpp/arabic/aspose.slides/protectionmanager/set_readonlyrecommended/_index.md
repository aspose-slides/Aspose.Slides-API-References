---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides للـ C++ مرجع واجهة برمجة التطبيقات
description: يضبط توصية القراءة-فقط. اكتب bool.
type: docs
weight: 92
url: /ar/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) طريقة

يضبط توصية القراءة-فقط. اكتب **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## ملاحظات

يعرض الشيفرة العينية التالية كيفية ضبط PowerPoint [Presentation](../../presentation/) إلى وضع القراءة-فقط في C# باستخدام [Aspose.Slides](../../). 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [ProtectionManager](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)