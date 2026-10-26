---
title: ReadState
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan keadaan pembaca.
type: docs
weight: 703
url: /id/system.xml/readstate/
---
## ReadState enum


Menentukan keadaan pembaca.

```cpp
enum class ReadState
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Initial | 0 | Metode [XmlReader::Read](../xmlreader/read/) belum dipanggil. |
| Interactive | 1 | Metode [XmlReader::Read](../xmlreader/read/) telah dipanggil. Metode tambahan dapat dipanggil pada pembaca. |
| Error | 2 | Terjadi kesalahan yang mencegah operasi baca untuk melanjutkan. |
| EndOfFile | 3 | Akhir berkas telah berhasil dicapai. |
| Closed | 4 | Metode [XmlReader::Close](../xmlreader/close/) telah dipanggil. |

## Lihat Juga

* Ruang nama [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)