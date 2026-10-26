---
title: GetByteCount()
second_title: Aspose.Slides untuk Referensi API C++
description: Mendapatkan jumlah byte yang diperlukan untuk mengkodekan sebuah buffer.
type: docs
weight: 40
url: /id/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metode


Mendapatkan jumlah byte yang diperlukan untuk mengkodekan sebuah buffer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter untuk dienkode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Jumlah karakter untuk dienkode. |
| flush | **bool** | Jika true, membersihkan keadaan encoder internal setelah perhitungan. |

### Nilai Kembalian

Jumlah byte yang diperlukan untuk mengkodekan buffer.

## ICUEncoder::GetByteCount(const char_t *, int, bool) metode


Mendapatkan jumlah byte yang diperlukan untuk mengkodekan sebuah buffer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const char_t * | Karakter untuk dienkode. |
| count | int | Jumlah karakter untuk dienkode. |
| flush | **bool** | Jika true, membersihkan keadaan encoder internal setelah perhitungan. |

### Nilai Kembalian

Jumlah byte yang diperlukan untuk mengkodekan buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ICUEncoder](../)
* RuangNama [System::Text](../../)
* Library [Aspose.Slides](../../../)