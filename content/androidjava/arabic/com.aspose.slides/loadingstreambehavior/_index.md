---
title: LoadingStreamBehavior
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يُعتبر java.io.InputStream الممرَّر إلى طريقة ككائن كبير ثنائي (BLOB) انظر الوصف.
type: docs
url: /ar/com.aspose.slides/loadingstreambehavior/
---
**الوراثة:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

يُعتبر java.io.InputStream الممرَّر إلى طريقة ككائن كبير ثنائي (BLOB) (انظر وصف [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). تحدد قيم هذا التعداد كيفية معاملة java.io.InputStream عند تمريره إلى الطريقة. حسب المتطلبات، يمكن اتخاذ قرارات مختلفة لتوفير أكثر السلوك كفاءة.

## الحقول

| الحقل | الوصف |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | سيتم قراءة التدفق حتى النهاية ثم إصداره - أي |
| [KeepLocked](#KeepLocked) | سيتم قفل التدفق داخل الكائن [IPresentation](../../com.aspose.slides/ipresentation)، أي |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

سيتم قراءة التدفق حتى النهاية ثم إصداره - أي سيتم ضمان أن هذا التدفق لن يتم استخدامه من قبل كائن [IPresentation](../../com.aspose.slides/ipresentation) في المستقبل. يمكن إغلاقه بواسطة كود العميل أو استخدامه بأي طريقة أخرى.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // يمكن إغلاق التدفق، فهو لم يعد مطلوبًا لكائن "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

سيتم قفل التدفق داخل الكائن [IPresentation](../../com.aspose.slides/ipresentation)، أي سيتم نقل ملكية التدفق. سيكون الكائن [IPresentation](../../com.aspose.slides/ipresentation) مسؤولاً عن التخلص الصحيح من التدفق عندما يتم التخلص من هذا الكائن نفسه. هذا السلوك مفيد للغاية عندما تحتاج إلى تسلسل ملف BLOB كبير (مثل فيديو أو صوت كبير - راجع وصف [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) وتريد منع تحميل هذا الملف في الذاكرة أو مشاكل أداء أخرى. يمكنك فقط فتح java.io.FileInputStream لهذا الملف وتمريره إلى طريقة، مختاراً [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // لا ينبغي إغلاق التدفق أو التفاعل معه بأي طريقة أخرى، سيؤدي ذلك إلى خطأ في طريقة Save.
>    // سيستخدم fileStream للحفظ، مما سيمنع استهلاك الذاكرة العالي
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
