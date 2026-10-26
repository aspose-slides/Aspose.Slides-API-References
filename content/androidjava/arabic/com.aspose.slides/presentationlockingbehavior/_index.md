---
title: PresentationLockingBehavior
second_title: Aspose.Slides لـ Android عبر مرجع Java API
description: يمثل السلوك المتعلق بمعالجة  ملف المصدر أو  java.io.InputStream أثناء التحميل والعمل مع كائن من .
type: docs
url: /ar/com.aspose.slides/presentationlockingbehavior/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

يمثل السلوك المتعلق بمعالجة مصدر [IPresentation](../../com.aspose.slides/ipresentation) (ملف أو java.io.InputStream) أثناء تحميله والعمل معه ككائن من [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

المصدر هو المعامل الممرّر إلى مُنشئ [IPresentation](../../com.aspose.slides/ipresentation). في المثال أدناه، المصدر هو ملف "pres.pptx": بالنسبة لهذا المثال، سيُقفل المصدر (ملف "pres.pptx") طوال عمر كائن [IPresentation](../../com.aspose.slides/ipresentation)، أي لا يمكن تغييره أو حذفه بواسطة العملية الأخرى.
## Fields

| Field | Description |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | سيُقفل المصدر فقط لفترة تنفيذ مُنشئ [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | سيُقفل المصدر طوال عمر كائن [IPresentation](../../com.aspose.slides/ipresentation)، حتى يتم التخلص منه. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

سيُقفل المصدر فقط لفترة تنفيذ مُنشئ [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

إذا تم تعيين ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) إلى false، ستُحمَّل جميع الكائنات الثنائية الكبيرة (BLOBs) في الذاكرة. وإلا، قد تُستَخدم طرق أخرى مثل الملفات المؤقتة.

--------------------

هذا السلوك أبطأ من [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked)، وإذا كان بإمكان تمرير ملكية المصدر إلى [IPresentation](../../com.aspose.slides/ipresentation)، يُنصَح باستخدام [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

سيُقفل المصدر طوال عمر كائن [IPresentation](../../com.aspose.slides/ipresentation)، حتى يتم التخلص منه.

--------------------

يجب تعيين [IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) إلى true لاستخدام هذا السلوك، وإلا سيُطرح استثناء.

--------------------

يُوصى بهذا السلوك، فهو أسرع ويستهلك ذاكرة أقل من [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).