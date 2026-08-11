---
title: LoadExternalFonts()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف مجلدات إضافية للبحث عن الخطوط.
type: docs
weight: 1
url: /ar/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) طريقة

يضيف مجلدات إضافية للبحث عن الخطوط.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | الدلائل لقراءة الخطوط الإضافية. |

## ملاحظات

المثال التالي يوضح كيفية تحميل خطوط مخصصة من .TTF 
```cpp
// مسار دليل المستندات.
System::String dataDir = u"C:\\";

// مجلدات للبحث عن الخطوط
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// تحميل خطوط الدليل المخصص
FontsLoader::LoadExternalFonts(folders);

// تنفيذ بعض العمل وعرض التقديم/الشرائح
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// مسح ذاكرة الخطوط المؤقتة
FontsLoader::ClearCache();
```

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [FontsLoader](../)
* مساحة اسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)