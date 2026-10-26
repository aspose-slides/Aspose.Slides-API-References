---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili sebuah instance percakapan.
type: docs
url: /id/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Mewakili sebuah instance percakapan. Tidak seperti panggilan AI reguler, percakapan mempertahankan seluruh konteks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Mengirim pesan permintaan percakapan termasuk seluruh konteks dan mengembalikan respons. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Mengirim pesan permintaan percakapan termasuk seluruh konteks dan mengembalikan respons.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| instruction | java.lang.String | Instruksi atau pesan yang akan diproses oleh model AI. |

**Mengembalikan:**
java.lang.String - Pesan yang dihasilkan oleh model AI sebagai respons terhadap instruksi yang diberikan dalam konteks percakapan.