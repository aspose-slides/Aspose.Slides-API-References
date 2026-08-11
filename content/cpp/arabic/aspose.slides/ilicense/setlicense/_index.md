---
title: SetLicense()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرخص المكوّن.
type: docs
weight: 1
url: /ar/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) طريقة


يرخص المكوّن.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```


### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | يمكن أن يكون اسم ملف كامل أو مختصر أو اسم مورد مضمّن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |
## ملاحظات



يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. مجلد تجميع المكوّن.

3. مجلد تجميع العميل المستدعي.

4. مجلد تجميع الدخول.

5. مورد مضمّن في تجميع العميل المستدعي.

**ملاحظة:** على .NET Compact Framework، يحاول العثور على الترخيص فقط في هذه المواقع:

1. مسار صريح.

2. مورد مضمّن في تجميع العميل المستدعي.

في هذا المثال، سيتم محاولة العثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، في مجلد تجميع الدخول ثم في الموارد المضمنة للتجميع المستدعي. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) طريقة


يرخص المكوّن.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```


### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق يحتوي على الترخيص. |
## ملاحظات



استخدم هذه الطريقة لتحميل ترخيص من تدفق.


```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ILicense](../)
* فئة [Stream](../../../system.io/stream/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)