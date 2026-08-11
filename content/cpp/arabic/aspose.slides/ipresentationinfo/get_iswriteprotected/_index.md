---
title: get_IsWriteProtected()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على قيمة تشير إلى ما إذا كان عرضًا مرتبطًا محميًا ضد الكتابة.
type: docs
weight: 27
url: /ar/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() طريقة

يحصل على قيمة تشير إلى ما إذا كان عرض مرتبط محميًا ضد الكتابة.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## ملاحظات

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

إذا كان العرض محمياً بكلمة مرور للفتح، فإن قيمة الخاصية تساوي NotDefined. راجع تعداد [NullableBool](../../nullablebool/).

## انظر أيضًا

* Enum [NullableBool](../../nullablebool/)
* الفئة [IPresentationInfo](../)
* النطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)