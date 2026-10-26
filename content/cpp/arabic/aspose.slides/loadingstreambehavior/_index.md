---
title: LoadingStreamBehavior
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يُعتبر الـ System::IO::Stream الممرّر إلى طريقة ما ككائن ثنائي كبير (BLOB) (انظر وصف IBlobManagementOptions). تحدد قيم هذا التعداد كيف يجب التعامل مع الـ System::IO::Stream عندما يُمرّر إلى الطريقة. اعتمادًا على المتطلبات، يمكن اتخاذ قرارات مختلفة لتوفير أكثر السلوكيات كفاءة."
type: docs
weight: 6735
url: /ar/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior تعداد

The [System::IO::Stream](../../system.io/stream/) passed to a method is considered as a Binary Large Object (BLOB) (see [IBlobManagementOptions](../iblobmanagementoptions/) description). Values of this enumeration identify how the [System::IO::Stream](../../system.io/stream/) should be treated when it passed to the method. Depending on the requirements, different decisions could be made to provide the most efficient behavior.

```cpp
enum class LoadingStreamBehavior
```

### Values

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | سيُقرأ الدفق حتى النهاية ثم يُحرَّر - أي سيُضمن أن هذا الدفق لن يُستَخدم من قبل كائن [IPresentation](../ipresentation/) في المستقبل. يمكن إغلاقه بواسطة شفرة العميل أو استخدامه بأي طريقة أخرى. |
| KeepLocked | 1 | سيُقفل الدفق داخل كائن [IPresentation](../ipresentation/)، أي سيتم نقل ملكية الدفق. سيكون كائن [IPresentation](../ipresentation/) مسؤولاً عن التخلص الصحيح من الدفق عندما يتم التخلص من هذا الكائن نفسه. هذا السلوك مفيد جداً عندما تحتاج إلى تسلسل ملف BLOB كبير (مثل فيديو أو صوت كبير - انظر وصف [IBlobManagementOptions](../iblobmanagementoptions/)) وتريد منع تحميل هذا الملف إلى الذاكرة أو مشاكل أداء أخرى. يمكنك فقط فتح [System::IO::FileStream](../../system.io/filestream/) لهذا الملف وتمريره إلى طريقة، باختيار [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## انظر أيضًا

* النطاق [Aspose::Slides](../)
* المكتبة [Aspose.Slides](../../)