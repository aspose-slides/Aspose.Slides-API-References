---
title: ReadPresentation()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بقراءة عرض تقديمي موجود من المصفوفة
type: docs
weight: 40
url: /ar/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) طريقة

يقوم بقراءة عرض تقديمي موجود من المصفوفة

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المصفوفة للقراءة |

### قيمة الإرجاع

العرض المقروء

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) طريقة

يقوم بقراءة عرض تقديمي موجود من المصفوفة مع خيارات تحميل إضافية

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المصفوفة للقراءة |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | خيارات التحميل |

### قيمة الإرجاع

العرض المقروء

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) طريقة

يقوم بقراءة عرض تقديمي موجود من الدفق

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإدخال للقراءة |

### قيمة الإرجاع

العرض المقروء

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) طريقة

يقوم بقراءة عرض تقديمي موجود من الدفق مع خيارات تحميل إضافية

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإدخال للقراءة |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | خيارات التحميل |

### قيمة الإرجاع

العرض المقروء

## PresentationFactory::ReadPresentation(System::String) طريقة

يقوم بقراءة عرض تقديمي موجود من الملف

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | اسم الملف |

### قيمة الإرجاع

العرض المقروء

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) طريقة

يقوم بقراءة عرض تقديمي موجود من الملف مع خيارات تحميل إضافية

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | اسم الملف |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | خيارات التحميل |

### قيمة الإرجاع

العرض المقروء

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [IPresentation](../../ipresentation/)
* فئة [PresentationFactory](../)
* فئة [ILoadOptions](../../iloadoptions/)
* فئة [Stream](../../../system.io/stream/)
* فئة [String](../../../system/string/)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)