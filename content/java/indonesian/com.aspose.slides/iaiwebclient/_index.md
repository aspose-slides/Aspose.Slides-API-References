---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: Antarmuka klien AI Web.
type: docs
url: /id/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Antarmuka klien AI Web. Antarmuka ini memungkinkan mengganti berbagai model bahasa AI. Kelas yang mengimplementasikan antarmuka ini seharusnya digunakan bersama SlidesAIAgent.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Mengirim instruksi chat ke model AI menggunakan instance HttpConnection yang disediakan dan mengembalikan pesan respons ke instruksi yang diberikan. |
| [createConversation()](#createConversation--) | Membuat sebuah instance percakapan. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Mengirim instruksi chat ke model AI menggunakan instance HttpConnection yang disediakan dan mengembalikan pesan respons ke instruksi yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| instruction | java.lang.String | Instruksi atau pesan yang akan diproses oleh model AI. |

**Mengembalikan:**
java.lang.String - Pesan yang dihasilkan oleh model AI sebagai respons terhadap instruksi yang diberikan.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Membuat sebuah instance percakapan. Tidak seperti panggilan AI reguler, percakapan mempertahankan seluruh konteks.

**Mengembalikan:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Sebuah instance [IAIConversation](../../com.aspose.slides/iaiconversation).