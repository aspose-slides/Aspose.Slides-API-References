---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Java API Referansı
description: Bir metoda geçirilen java.io.InputStream, Binary Large Object (BLOB) olarak kabul edilir. Açıklamaya bakınız.
type: docs
url: /tr/com.aspose.slides/loadingstreambehavior/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Bir metoda geçirilen java.io.InputStream, Binary Large Object (BLOB) olarak kabul edilir ([IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) açıklamasına bakınız). Bu enum değerleri, java.io.InputStream'in metoda geçirildiğinde nasıl ele alınacağını belirler. Gereksinimlere bağlı olarak, en verimli davranışı sağlamak için farklı kararlar verilebilir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Akış sonuna kadar okunacak ve ardından serbest bırakılacak - yani |
| [KeepLocked](#KeepLocked) | Akış [IPresentation](../../com.aspose.slides/ipresentation) nesnesi içinde kilitlenecek, yani |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Akış sonuna kadar okunacak ve ardından serbest bırakılacak - yani bu akışın gelecekte [IPresentation](../../com.aspose.slides/ipresentation) örneği tarafından kullanılmayacağı garanti edilecektir. İstemci kodu tarafından kapatılabilir veya başka bir şekilde kullanılabilir.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // akış kapatılabilir, artık "pres" nesnesi için gerekli değil.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Akış [IPresentation](../../com.aspose.slides/ipresentation) nesnesi içinde kilitlenecek, yani akışın sahipliği devredilecektir. [IPresentation](../../com.aspose.slides/ipresentation) nesnesi, bu nesne kendisi yok edildiğinde akışı doğru şekilde temizlemekten sorumlu olacaktır. Bu davranış, büyük bir BLOB dosyasını (örneğin büyük bir video veya ses - [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) açıklamasına bakınız) dizileştirmeniz gerektiğinde ve bu dosyanın belleğe yüklenmesini veya diğer performans sorunlarını önlemek istediğinizde son derece faydalıdır. Sadece bu dosya için java.io.FileInputStream açabilir ve bir metoda geçerek [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior seçebilirsiniz.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Akışı kapatmamalısınız veya başka bir şekilde onunla etkileşime girmemelisiniz, bu Save metodunda hataya yol açar.
>    // fileStream kaydetme için kullanılacak, bu da yüksek bellek tüketimini önleyecektir.
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
