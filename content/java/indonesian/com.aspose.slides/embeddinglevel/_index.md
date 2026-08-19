---
title: EmbeddingLevel
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili hak lisensi untuk menyematkan font.
type: docs
url: /id/com.aspose.slides/embeddinglevel/
---
**Warisan:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum  
```
public final class EmbeddingLevel extends System.Enum
```

Mewakili hak lisensi untuk menyematkan font.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Installable](#Installable) | Font dengan pengaturan ini menunjukkan bahwa mereka dapat disematkan dan dipasang secara permanen pada sistem remote oleh sebuah aplikasi. |
| [Restricted](#Restricted) | Font yang hanya memiliki bit ini yang diatur tidak boleh dimodifikasi, disematkan, atau dipertukarkan dengan cara apapun tanpa terlebih dahulu mendapatkan izin dari pemilik sah. |
| [PreviewPrint](#PreviewPrint) | Ketika bit ini diatur, font dapat disematkan, dan dimuat secara sementara pada sistem remote. |
| [Editable](#Editable) | Ketika bit ini diatur, font dapat disematkan tetapi hanya boleh dipasang secara sementara pada sistem lain. |
| [NoSubsetting](#NoSubsetting) | Ketika bit ini diatur, font tidak boleh dipotong (subsetted) sebelum disematkan. |
| [BitmapOnly](#BitmapOnly) | Ketika bit ini diatur, hanya bitmap yang terdapat dalam font yang dapat disematkan. |

### Installable {#Installable}
```
public static final int Installable
```

Font dengan pengaturan ini menunjukkan bahwa mereka dapat disematkan dan dipasang secara permanen pada sistem remote oleh sebuah aplikasi. Pengguna sistem remote memperoleh hak, kewajiban, dan lisensi yang identik untuk font tersebut seperti pembeli asli font, dan tunduk pada perjanjian lisensi pengguna akhir, hak cipta, paten desain, dan/atau merek dagang yang sama seperti pembeli asli.

### Restricted {#Restricted}
```
public static final int Restricted
```

Font yang hanya memiliki bit ini yang diatur tidak boleh dimodifikasi, disematkan, atau dipertukarkan dengan cara apapun tanpa terlebih dahulu mendapatkan izin dari pemilik sah.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Ketika bit ini diatur, font dapat disematkan, dan dimuat secara sementara pada sistem remote. Dokumen yang berisi font Preview & Print harus dibuka "read-only"; tidak ada pengeditan yang dapat diterapkan pada dokumen.

### Editable {#Editable}
```
public static final int Editable
```

Ketika bit ini diatur, font dapat disematkan tetapi hanya boleh dipasang secara sementara pada sistem lain. Berbeda dengan font Preview & Print, dokumen yang berisi font Editable dapat dibuka untuk dibaca, pengeditan diizinkan, dan perubahan dapat disimpan.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Ketika bit ini diatur, font tidak boleh dipotong (subsetted) sebelum disematkan. Pembatasan penyematan lain yang ditentukan pada bit 0-3 dan 9 juga berlaku.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Ketika bit ini diatur, hanya bitmap yang terdapat dalam font yang dapat disematkan. Tidak ada data outline yang dapat disematkan. Jika tidak ada bitmap yang tersedia dalam font, maka font dianggap tidak dapat disematkan dan layanan penyematan akan gagal.