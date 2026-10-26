---
title: LoadingStreamBehavior
second_title: Referensi API Java Aspose.Slides untuk Android
description: java.io.InputStream yang diteruskan ke suatu metode dianggap sebagai Binary Large Object (BLOB) lihat deskripsi.
type: docs
url: /id/com.aspose.slides/loadingstreambehavior/
---
**Pewarisan:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream yang diteruskan ke suatu metode dianggap sebagai Binary Large Object (BLOB) (lihat deskripsi [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Nilai-nilai enumerasi ini mengidentifikasi bagaimana java.io.InputStream harus diperlakukan ketika diteruskan ke metode. Bergantung pada kebutuhan, keputusan berbeda dapat dibuat untuk memberikan perilaku yang paling efisien.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Aliran akan dibaca sampai akhir dan kemudian dilepaskan - i.e. |
| [KeepLocked](#KeepLocked) | Aliran akan dikunci di dalam objek [IPresentation](../../com.aspose.slides/ipresentation), i.e. |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Aliran akan dibaca sampai akhir dan kemudian dilepaskan - i.e. akan dijamin bahwa aliran ini tidak akan digunakan oleh instansi [IPresentation](../../com.aspose.slides/ipresentation) di masa mendatang. Aliran dapat ditutup oleh kode klien atau digunakan dengan cara lain.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // stream dapat ditutup, tidak lagi diperlukan untuk objek "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Aliran akan dikunci di dalam objek [IPresentation](../../com.aspose.slides/ipresentation), i.e. kepemilikan aliran akan dipindahkan. Objek [IPresentation](../../com.aspose.slides/ipresentation) akan bertanggung jawab untuk membuang aliran dengan benar ketika objek ini dibuang sendiri. Perilaku ini sangat berguna ketika Anda perlu men-serialize file BLOB besar (seperti video atau audio besar - lihat deskripsi [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) dan ingin mencegah memuat file ini ke dalam memori atau masalah kinerja lainnya. Anda cukup membuka java.io.FileInputStream untuk file ini dan meneruskannya ke suatu metode, memilih [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Anda tidak boleh menutup aliran atau berinteraksi dengannya dengan cara lain apa pun, hal ini akan menyebabkan error pada metode Save.
>    // fileStream akan digunakan untuk penyimpanan, yang akan mencegah konsumsi memori tinggi
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
