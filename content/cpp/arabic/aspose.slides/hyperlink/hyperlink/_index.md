---
title: Hyperlink()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إنشاء نسخة من ارتباط تشعبي.
type: docs
weight: 339
url: /ar/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) المُنشئ


إنشاء نسخة من ارتباط تشعبي.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```


### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) المُنشئ


إنشاء نسخة من ارتباط تشعبي يشير إلى شريحة محددة. ملاحظة: يجب إسناد الارتباط التشعبي المُنشأ إلى كائن من نفس العرض التقديمي، وإلا سيتم حفظ الرابط كـ NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```


### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | الشريحة المستهدفة. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) المُنشئ


إنشاء نسخة من ارتباط تشعبي باستخدام ارتباط تشعبي آخر كمصدر، مع تجاوز الخصائص الثانوية.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```


### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | الارتباط التشعبي المصدر |
| targetFrame | [System::String](../../../system/string/) | الإطار المستهدف |
| tooltip | [System::String](../../../system/string/) | نص تلميح الأدوات |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [Hyperlink](../)
* فئة [ISlide](../../islide/)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)