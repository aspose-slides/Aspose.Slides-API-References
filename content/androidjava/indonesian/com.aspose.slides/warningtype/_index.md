---
title: WarningType
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili jenis peringatan.
type: docs
url: /id/com.aspose.slides/warningtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Mewakili jenis peringatan.
## Fields

| Bidang | Deskripsi |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | Masalah telah terdeteksi dalam dokumen sumber yang membuat sangat mungkin dokumen tidak dapat dibuka jika disimpan dalam format aslinya. |
| [DataLoss](#DataLoss) | Teks/diagram/gambar atau data lain akan sepenuhnya hilang baik dari pohon dokumen setelah dimuat, maupun dari dokumen yang dibuat setelah disimpan. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Kehilangan format utama. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Kehilangan format kecil. |
| [CompatibilityIssue](#CompatibilityIssue) | Ini adalah masalah yang diketahui yang akan mencegah dokumen dibuka oleh agen pengguna tertentu, atau versi sebelumnya dari agen pengguna. |
| [UnexpectedContent](#UnexpectedContent) | Beberapa konten dalam dokumen sumber tidak dapat dikenali (misalnya |

### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```

Masalah telah terdeteksi dalam dokumen sumber yang membuat sangat mungkin dokumen tidak dapat dibuka jika disimpan dalam format aslinya.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```

Teks/diagram/gambar atau data lain akan sepenuhnya hilang baik dari pohon dokumen setelah dimuat, maupun dari dokumen yang dibuat setelah disimpan.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```

Kehilangan format utama.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```

Kehilangan format kecil.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```

Ini adalah masalah yang diketahui yang akan mencegah dokumen dibuka oleh agen pengguna tertentu, atau versi sebelumnya dari agen pengguna.

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```

Beberapa konten dalam dokumen sumber tidak dapat dikenali (misalnya tidak didukung), hal ini mungkin atau tidak mungkin menyebabkan masalah atau mengakibatkan kehilangan data/pengformatan.