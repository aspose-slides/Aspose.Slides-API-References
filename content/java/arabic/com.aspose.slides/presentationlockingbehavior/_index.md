---
title: PresentationLockingBehavior
second_title: مرجع API لـ Aspose.Slides للغة جافا
description: يمثل السلوك المتعلق بمعالجة  ملف المصدر أو  java.io.InputStream أثناء التحميل والعمل مع نسخة من .
type: docs
url: /ar/com.aspose.slides/presentationlockingbehavior/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

يمثل السلوك المتعلق بمعالجة مصدر [IPresentation](../../com.aspose.slides/ipresentation) (ملف أو java.io.InputStream) أثناء التحميل والعمل مع نسخة من [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

المصدر هو المعامل الممرّر إلى مُنشئ [IPresentation](../../com.aspose.slides/ipresentation). في المثال أدناه، المصدر هو ملف "pres.pptx": بالنسبة لهذا المثال، سيُقفل المصدر (ملف "pres.pptx") طوال مدة حياة نسخة [IPresentation](../../com.aspose.slides/ipresentation)، أي لا يمكن تغييره أو حذفه بواسطة العملية الأخرى.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | سيُقفل المصدر فقط لمدة تنفيذ مُنشئ [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | سيُقفل المصدر طوال مدة حياة نسخة [IPresentation](../../com.aspose.slides/ipresentation)، حتى يتم التخلص منها. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```


سيُقفل المصدر فقط لمدة تنفيذ مُنشئ [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

إذا تم ضبط ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) على false، سيتم تحميل جميع الـBLOBs في الذاكرة. وإلا، قد تُستخدم وسائل أخرى مثل الملفات المؤقتة.

--------------------

هذا السلوك أبطأ من [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked)، وإذا كان من الممكن تمرير ملكية المصدر إلى [IPresentation](../../com.aspose.slides/ipresentation)، يُنصح باستخدام [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


سيُقفل المصدر طوال مدة حياة نسخة [IPresentation](../../com.aspose.slides/ipresentation)، حتى يتم التخلص منها.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) يجب تعيينه إلى true لاستخدام هذا السلوك، وإلا سيتم رمي استثناء.

--------------------

يُوصى بهذا السلوك، فهو أسرع ويستهلك ذاكرة أقل من [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).