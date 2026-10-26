---
title: LoadingStreamBehavior
second_title: Referensi API Aspose.Slides untuk Java
description: java.io.InputStream yang diteruskan ke sebuah metode dianggap sebagai Binary Large Object (BLOB) lihat deskripsi.
type: docs
url: /id/com.aspose.slides/loadingstreambehavior/
---
**Warisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream yang diteruskan ke sebuah metode dianggap sebagai Binary Large Object (BLOB) (lihat deskripsi [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Nilai-nilai enumerasi ini mengidentifikasi bagaimana java.io.InputStream harus diperlakukan ketika diteruskan ke metode. Bergantung pada kebutuhan, keputusan yang berbeda dapat dibuat untuk memberikan perilaku yang paling efisien.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Aliran akan dibaca hingga akhir dan kemudian dilepaskan - yaitu |
| [KeepLocked](#KeepLocked) | Aliran akan dikunci di dalam objek [IPresentation](../../com.aspose.slides/ipresentation), yaitu |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Aliran akan dibaca hingga akhir dan kemudian dilepaskan - yaitu akan dijamin bahwa aliran ini tidak akan digunakan oleh instance [IPresentation](../../com.aspose.slides/ipresentation) di masa depan. Aliran ini dapat ditutup oleh kode klien atau digunakan dengan cara lain.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // aliran dapat ditutup, tidak lagi diperlukan untuk objek "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Aliran akan dikunci di dalam objek [IPresentation](../../com.aspose.slides/ipresentation), yaitu kepemilikan aliran akan dipindahkan. Objek [IPresentation](../../com.aspose.slides/ipresentation) akan bertanggung jawab untuk secara benar membuang aliran ketika objek ini dibuang sendiri. Perilaku ini sangat berguna ketika Anda perlu men-serialize file BLOB besar (seperti video atau audio besar - lihat deskripsi [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) dan ingin mencegah memuat file ini ke memori atau masalah kinerja lainnya. Anda dapat langsung membuka java.io.FileInputStream untuk file ini dan meneruskannya ke sebuah metode, dengan memilih [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Anda tidak boleh menutup aliran atau berinteraksi dengannya dengan cara lain, ini akan menyebabkan error pada metode Save.
>    // Aliran file akan digunakan untuk penyimpanan, yang akan mencegah konsumsi memori tinggi
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```