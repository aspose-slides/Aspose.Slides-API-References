---
title: ReadPresentation()
second_title: مرجع API Aspose.Slides للغة C++
description: يقرأ عرض تقديمي موجود من مصفوفة
type: docs
weight: 27
url: /ar/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) طريقة

يقوم بقراءة عرض موجود من المصفوفة

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المصفوفة للقراءة |

### قيمة الإرجاع

قراءة العرض

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) طريقة

يقوم بقراءة عرض موجود من المصفوفة مع خيارات تحميل إضافية

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المصفوفة للقراءة |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | خيارات التحميل |

### قيمة الإرجاع

قراءة العرض

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) طريقة

يقوم بقراءة عرض موجود من الدفق

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإدخال للقراءة |

### قيمة الإرجاع

قراءة العرض

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) طريقة

يقوم بقراءة عرض موجود من الدفق مع خيارات تحميل إضافية

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإدخال للقراءة |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | خيارات التحميل |

### قيمة الإرجاع

قراءة العرض

## IPresentationFactory::ReadPresentation(System::String) طريقة

يقوم بقراءة عرض موجود من الملف

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | اسم الملف |

### قيمة الإرجاع

قراءة العرض

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) طريقة

يقوم بقراءة عرض موجود من الدفق مع خيارات تحميل إضافية

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | اسم الملف |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | خيارات التحميل |

### قيمة الإرجاع

قراءة العرض

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IPresentation](../../ipresentation/)
* فئة [IPresentationFactory](../)
* فئة [ILoadOptions](../../iloadoptions/)
* فئة [Stream](../../../system.io/stream/)
* فئة [String](../../../system/string/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)