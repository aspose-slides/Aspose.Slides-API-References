---
title: LoadingStreamBehavior
second_title: مرجع Aspose.Slides للغة Java
description: يُعتبر java.io.InputStream الممرَّر إلى طريقة ما ككائن كبير ثنائي (BLOB) انظر الوصف.
type: docs
url: /ar/com.aspose.slides/loadingstreambehavior/
---
**الوراثة:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

يُعتَبَر java.io.InputStream الممرَّر إلى طريقة ما ككائن كبير ثنائي (BLOB) (انظر وصف [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). تحدد قيم هذا التعداد كيف يجب التعامل مع java.io.InputStream عندما يتم تمريره إلى الطريقة. اعتمادًا على المتطلبات، يمكن اتخاذ قرارات مختلفة لتوفير السلوك الأكثر كفاءة.
## الحقول

| الحقل | الوصف |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | سيتم قراءة التدفق حتى النهاية ثم تحريره - أي |
| [KeepLocked](#KeepLocked) | سيتم قفل التدفق داخل كائن [IPresentation](../../com.aspose.slides/ipresentation)، أي |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

سيتم قراءة التدفق حتى النهاية ثم تحريره - أي سيتم ضمان أن هذا التدفق لن يستخدمه مثال [IPresentation](../../com.aspose.slides/ipresentation) في المستقبل. يمكن إغلاقه بواسطة شفرة العميل أو استخدامه بأي طريقة أخرى.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // يمكن إغلاق التدفق، لم يعد مطلوبًا لكائن "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

سيتم قفل التدفق داخل كائن [IPresentation](../../com.aspose.slides/ipresentation)، أي سيتم نقل ملكية التدفق. سيكون كائن [IPresentation](../../com.aspose.slides/ipresentation) مسؤولاً عن التخلص الصحيح من التدفق عندما يتم التخلص من هذا الكائن نفسه. هذا السلوك مفيد جدًا عندما تحتاج إلى تسلسل ملف BLOB كبير (مثل فيديو أو صوت كبير - انظر وصف [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) وتريد منع تحميل هذا الملف في الذاكرة أو تجنب مشاكل الأداء الأخرى. يمكنك فقط فتح java.io.FileInputStream لهذا الملف وتمريره إلى طريقة، مختارًا [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // لا يجب إغلاق التدفق أو التفاعل معه بأي طريقة أخرى، سيسبب ذلك خطأً في طريقة Save.
>    // سيُستخدم fileStream للحفظ، مما سيمنع استهلاك الذاكرة العالي
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
