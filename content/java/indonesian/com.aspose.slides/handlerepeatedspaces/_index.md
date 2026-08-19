---
title: HandleRepeatedSpaces
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan cara penanganan karakter spasi reguler berulang selama ekspor Markdown.
type: docs
url: /id/com.aspose.slides/handlerepeatedspaces/
---
**Warisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Menentukan cara penanganan karakter spasi reguler berulang selama ekspor Markdown.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [None](#None) | Semua spasi dipertahankan sebagai karakter spasi reguler tanpa perubahan. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Mengubah urutan dua atau lebih spasi reguler berurutan dengan cara bergantian antara karakter spasi reguler dan entitas spasi tak terputus NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Mengubah urutan dua atau lebih spasi reguler berurutan dengan mempertahankan spasi pertama sebagai karakter spasi reguler dan mengganti semua spasi berikutnya dengan entitas spasi tak terputus NBSP. |
### None {#None}
```
public static final int None
```

Semua spasi dipertahankan sebagai karakter spasi reguler tanpa perubahan. Tidak ada transformasi yang diterapkan, dan spasi berurutan yang banyak diekspor apa adanya.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Mengubah urutan dua atau lebih spasi reguler berurutan dengan cara bergantian antara karakter spasi reguler dan entitas spasi tak terputus NBSP. Spasi pertama selalu dipertahankan sebagai spasi reguler.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Mengubah urutan dua atau lebih spasi reguler berurutan dengan mempertahankan spasi pertama sebagai karakter spasi reguler dan mengganti semua spasi berikutnya dengan entitas spasi tak terputus NBSP.