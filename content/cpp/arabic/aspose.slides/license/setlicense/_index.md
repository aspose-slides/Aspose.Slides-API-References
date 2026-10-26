---
title: SetLicense()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرخص المكوّن.
type: docs
weight: 14
url: /ar/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) طريقة

Licenses the component.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | يمكن أن يكون اسم ملف كامل أو مختصر أو اسم مورد مضمّن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

## ملاحظات

Tries to find the license in the following locations:

1. Explicit path.
2. The folder of the component assembly.
3. The folder of the client's calling assembly.
4. The folder of the entry assembly.
5. An embedded resource in the client's calling assembly.

**ملاحظة:**في .NET Compact Framework، يحاول العثور على الترخيص فقط في هذه المواقع:

1. Explicit path.
2. An embedded resource in the client's calling assembly.

In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) طريقة

Licenses the component.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق يحتوي على الترخيص. |

## ملاحظات

Use this method to load a license from a stream.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [License](../)
* فئة [Stream](../../../system.io/stream/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)